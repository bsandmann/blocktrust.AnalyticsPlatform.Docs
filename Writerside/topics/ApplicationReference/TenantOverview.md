# Overview

The tenant is the main entry point to the **Analytics Platform**. From here you start configuring your data-pools and attach sessions to those pools.

## Pools
To process and visualize data, you must first establish a data pool. These pools aggregate all the Verifiable Credentials and Presentations you have gathered. Similar to sessions, pools are generally private, containing only the data you have imported. This design ensures distinct separation from other tenants and the various data pools within your own tenant. Creating different pools for specific objectives is advisable. For instance, a pool could be designated for data exclusively collected from diverse sources or for distinct purposes, or to distinguish between test data and production data.

Adding data to a pool can be accomplished through a dedicated ingestion endpoint for each pool or directly from the graph interface.

## Sessions
Analytics Sessions are built on one or more pools. A session enables users to visualize, search, and compare data from the connected pools. Access in a session is limited to the data within the attached pools, preventing any analysis of data outside these pools. This setup ensures a clear separation between tenants and different sessions, preventing any mix-up between test data and production data.

## Getting Started
Begin by creating a new pool or utilizing the default pool to import data via that pool's ingestion endpoint. Subsequently, create a new session (or use the default session) and link it to the pool containing the data you wish to analyze. Then, proceed to open the graph view.