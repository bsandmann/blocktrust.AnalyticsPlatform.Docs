# Pool Management

A pool serves as a repository for the Verifiable Credentials (VCs) and Verifiable Presentations (VPs) gathered. Upon the establishment of a new pool, it automatically generates a unique ingestion endpoint. VCs and VPs can be directly submitted to this endpoint via an HTTP-POST request. The acceptable submission formats are either raw JSON or a JWT.

Following its creation and the data ingestion process, the pool provides a basic statistical summary of the collected data within that specific pool. It's important to note that this summary exclusively represents the VPs and VCs that were explicitly ingested into the pool. Any DIDs, VCs, or VPs added indirectly are not included in this statistical overview.

Please be mindful that deleting a pool will also result in the removal of all sessions associated with it.