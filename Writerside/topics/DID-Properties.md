# DID-Properties

When selected a DID-Node on the graph, on the right side of the screen the properties of the DID are displayed. Depending on the DID-Method and the resolution-status slightly different information is displayed.

A resolvable DID-Document contains the following sections:
- DID-Identifier and Pool
- Resolution Status
- DID-Document

## DID-Identifier and Pool
This top section show the original identifer and this section is displayed for resolvalabe (public DIDs) as wells as non-resolvable DIDs. Next to the name, is a small icon to give the DID a more human readable name e.g. "Alice's DID" or "Issuer". This helps is analyzing the graph, as the names are often more meaningful than the actual identifier.
You can also add tags to the DID or all other entites, which can be used to filter the graph. This is especially useful when you have a large dataset and want to focus on a specific subset of the data.
Below the name and tags, the pool is displayed, where the DID is stored. This is especially useful when you have multiple pools and want to know where the DID is located. Furthermore you find a direct link to the pool-manager, a tool to filter down the contents of the pool (*Might still be disabled in the published version*).

## Resolution Status
The resolution status shows the user on which VDR the DID is located on (if resolvalbe). Next to the resolution status is a button to expand the resolution view to see the current version-Id of the DID-Document. In case multiple versions exists, it offers the options to go through the version history of the DID here.
Note that the view turns orange, when you select a different version form the the most current one. This is to indicate that the view is not the most current one and might be outdated and therefor maybe in conflict with other elements in the graph.

## DID-Document
The resolution result is presented in a graphical way, giving either Links or copy-paste buttons for certains values if available.
Idenpentend data-sources which have not directly been consumed in the ingestion process for that DID are also linked:

- For **did:prism** identifiers you can use the link in the top right of each document to directly get the underlying Cardano transaction, through which that specific DID has been created, updated or deactivated. The encoded operation can be found in the metadata-section of the linked Block-Explorer page. Details for interpreting the metadata can be found in the [DID-PRISM specification](https://github.com/input-output-hk/prism-did-method-spec/blob/main/w3c-spec/PRISM-method.md). For did:prism networks a **Resolver-API** is currently also available within the [OpenPrismNode](OPN-OpenPrismNode.md)
- For **did:indy** identifiers the link in the top right references an independently hosted instance of IndyScan:
    - For Sovrin Networks: [https://indyscan.io/](https://indyscan.io/)
    - For IDunion Networks: [https://idunion.esatus.com](https://idunion.esatus.com/)
    - For Indicio Networks: [https://indyscan.indiciotech.io](https://indyscan.indiciotech.io/)
    - For BC Gov Networks: [http://test.bcovrin.vonx.io](http://test.bcovrin.vonx.io/)
    - For CANdy Networks: [https://candyscan.idlab.org/](https://candyscan.idlab.org/)

The Resolver page is also available by using query parameters to directly resolve a specific DID e.g.

```https://statistics.blocktrust.dev/resolve?method=prism&network=preprod&identifier=64d59a62aa659b31da14cb3d63926d66a084859628b81838f709ea6f604a9204```

Using the **toggle-button** in the graphical interface lets the user switch between the raw JSON representation of the DID-Document and the graphical representation.

Note that the results inside the **`Metadata`** and **`Did-Resolution-Metadata`** section might slightly very with other resolution-results from other providers, as they are not completely standardized. Depending on the underlying did-method and network each provider might add additional metadata to the DID-Document, depending on what is available based on the individual infrastructure setup.

The **`Blocktrust Resolution Metadata`** section is purely informational to determine when the ingestion / resolution of that specific DID-Document initially occurred and which internal version of the resolver was used. It is not directly part of the [DID-Resolution specification](https://w3c.github.io/did-resolution/). In case of further processing of the Resolution-Result, this section can be omitted.

--
