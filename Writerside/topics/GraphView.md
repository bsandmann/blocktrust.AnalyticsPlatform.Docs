# Graph View

The Graph View is the first type of 'Session' currently supported by the Analytics Platform. It is designed to provide a visual representation of the relationships between Verifiable Credentials (VCs), Verifiable Presentations (VPs), and Decentralized Identifiers (DIDs) and Trust-Registries within a pool or across multiple pools. This feature is particularly useful for analyzing the connections between different entities and understanding the data flow within the ecosystem.

It is as its core a way to visually understand the relationship between a small set of nodes. While the numbers of entities represented in a Graph technicall doesn't have a limit, it isn't designed to show more than a few hundred nodes at a time. For larger datasets, it is recommend to filter those first into a smaller subset (ie. a seperate pool) before visualizing them in the Graph View. 

For future development an additional Session-Type is planed to better handle larger datasets in a visual way.

## Add new Elements to the Graph
To add new elements to the graph you have multiple options depending on the type of data:

### Decentralized Identifiers (DIDs)
- The simplest way to add a DID to a graph is by searching for that DID in the search menu in the upper left corner. It gives you several options to search through the complete dataset of all known DIDs, or just in a specific pool or a specific DID-Method. It supports fuzzy search, so you don't need to know the exact DID to find it. 
- DIDs can also be added by ingesting the identifier directly through an ingestion-endpoint into a pool. The most common way on the other hand to add DIDs is by adding the indirectly through the ingestion of a Verifiable Credential or Verifiable Presentation, which references the DID e.g. as holder or issuer.
- To add DIDs which are not yet in a pool and not know, you can add the identifier manually by clicking on the "Add DID" button in the left right corner. Note, that here you can only add the identifier and not a DID-Document. The reasoning behind this, is the assumption that DID-Documents are always public and therefore should already be known by the system for the supported networks. Adding a DID-Document for an unknown DID, but supported network, could potenially lead to inconsistencies in the data, especially when the DID-Document is later published on the network or different version of the DID-Document are in conflict with each other. A way to add arbitrary DID-Documents is also possible, but only for the DID-example method:
- For testing purposes DID-Documents for the `did:example` method can be added manually by clicking on the "Add DID-Doc" button in the left top corner. When adding multiple DID-Documents for the same DID, the system will automatically merge them together to a chain of versions. This is only possible for the `did:example` method, as it is the only method which is not connected to a real network. 

### Verifiable Credentials and Verifiable Presentations
- The most common way to add Verifiable Credentials and Verifiable Presentations to the graph is by ingesting them through an ingestion-endpoint into a pool. Prior to ingestion the system checks if this particular VC or VP is already known and if not, it will be added to the pool.
- Alternativly the VC or VP can be added as JSON directly to the graph by clicking on the "Add VC/VP"  button in the left top corner. While JSON is the most common format for VCs and VPs, the system also supports JWTs.

## Resolution
The resolution of the Graph happens automtically after adding elements to the graph. Known relationnship between DID and VCs/VPs are automatically displayed in the graph. In case connections are missing, try the "Show filters" button in the left buttom corner to enable the display of all connections, or select the type of connections you want to see.