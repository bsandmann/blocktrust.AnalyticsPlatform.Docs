# IndySync

IndySync is the internal software to ingest DID-Document for indy-networks into the Analytics-Platform. I heavily relies on [IndyScan](https://github.com/Patrik-Stas/indyscan) to scan the networks. The process involves processing the Elasticsearch data from IndyScan and transforming it into a valid DID-Document, including the available metadata on chain. Doing this in a linear way, allows also to build up the history of each DID-Document. This is an additional feature which is currently not available e.g. in the [Universal-Resolver](https://github.com/decentralized-identity/universal-resolver). The resulting DID-Resolution-Result Document is then ingested into the Analytics-Platform for further processing.

Basic architecure diagram of IndySync and its interactions with other components is shown below:
```mermaid
graph BT
    %% Networks
    SN[Sovrin Networks]
    IN[IDunion Networks]
    IndN[Indicio Networks]
    BCN[BC Gov Networks]
    CN[CANdy Networks]

    %% Indyscan
    IS[Indyscan Sovrin]
    II[Indyscan IDunion]
    IInd[Indyscan Indicio]
    IBC[Indyscan BC Gov]
    IC[Indyscan CANdy]

    %% Analytics Platform
    AP[Analytics Platform]

    %% Connections
    SN --syncs--> IS
    IN --syncs--> II
    IndN --syncs--> IInd
    BCN --syncs--> IBC
    CN --syncs--> IC

    IS --reads--> IndySync
    II --reads--> IndySync
    IInd --reads--> IndySync
    IBC --reads--> IndySync
    IC --reads--> IndySync

    IndySync --ingests--> AP
```