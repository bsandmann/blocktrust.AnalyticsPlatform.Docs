# PRISM

The *DID-PRISM* method is anchored on the *Cardano* Blockchain, an open, permissionless third-generation blockchain.

Anyone is free to create, update, deactivate, and publish DIDs according to the [specification](https://github.com/input-output-hk/prism-did-method-spec/blob/main/w3c-spec/PRISM-method.md) of the *DID-PRISM v2* method. Operations based on the obsolete *v1* method are no longer supported or tracked within the *Blocktrust Analytics* tooling.
The main client is the [Hyperledger Identus](https://github.com/hyperledger/identus) [cloud agent](https://github.com/hyperledger/identus-cloud-agent), initially developed by [IOG](https://iohk.io/) under the brand of [Atala](https://www.atalaprism.io/) and now open-source and maintained by the community together with IOG.
Development work is ongoing, primarily on the *Preprod* Network. Production use cases on the *Mainnet* have been existed for *v1* and now also showing up for *v2*.

## Mainnet 
Mainnet is the production network for the *Cardano* Blockchain. While over the last year multiple production use cases have been established using the now obsolete PRISM *v1* specification, only *v2* is supported with the *Blocktrust analytics tooling*, since *v1* was not aligned with the [W3C DID spec](https://www.w3.org/TR/did-core/).

Note that according to the [specification](https://github.com/input-output-hk/prism-did-method-spec/blob/main/w3c-spec/PRISM-method.md), the full DID-PRISM identifier for preprod DIDs looks identical to the ones on mainnet. To avoid confusion, a discriminator (did:prism:*mainnet*:123...) is added here. DIDs without any discriminator are always considered to be on *mainnet* only.

## Preprod
Preprod is one of multiple test-networks of the *Cardano* Blockchain and considered the final testing stage for release. This is true for core developments for the blockchain itself, as for PRISM-related products and services. Multiple projects run their own PRISM nodes, to facilitate the read/write operations of PRISM operations to the blockchain.

Note that according to the [specification](https://github.com/input-output-hk/prism-did-method-spec/blob/main/w3c-spec/PRISM-method.md), the full DID-PRISM identifier for preprod DIDs looks identical to the ones on *mainnet*. To avoid confusion, a discriminator (did:prism:*preprod*:123...) is added here. DIDs without any discriminator are always considered to be on *mainnet* only.