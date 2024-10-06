# Others

Depending on the type of Graph, you will find differnt kind of additional enties in the Graph View. This section gives an overview of those entities and their properties.

## Identity URI
This node respresent any kind of URI which is used as an entity in the graph. Usually you will encounter this kind of nodes, if a Credential is not using a DID as subject or issuer, but an URI (e.g. the URL of a school which issued a credential). The properties window currently only provides a link to the URI. In future version additional information about the URI will be displayed 
- like the DNS-Records pointing to the URI
- the DNS-History of the URI
- IP-Addresses associated with the URI and the geolocation
- the SSL-Certificate of the URI
- the WHOIS-Information of the URI

The main purpose of this future addions would be to determine the trustworthiness of the URI and the entity behind it. The lookup of the mentioned information would help to identify fraud through recently changed data.

## Service-Endpoints
Service-Endpoints are used to represent the endpoints of a DID-Document. These could be human-readable websites, but also services designed for machine-to-machine communication like DID-Comm endpoints. 

## Trust-Registry
There is currently no definitive standard on Trust-Registries and different implementations are used within different ecosystem. The current implemantion allows for reading the DIF-standart of a trust-registry and displaying the information in the properties window. Note, that the Trust-Registries must be set up before the session is started, to detect the relationship between the DIDs and the Trust-Registries correctly.

## JSON LD Contexts
JSON LD Contexts are used to define the context of a JSON-LD document. The context is used to map the keys of the JSON-LD document to the correct values. The context is used to define the meaning of the keys and values in the document. The context is usually a URL pointing to a JSON-LD document, which defines the mapping. The properties window currently only provides a link to the context. In future version additional information about the context will be displayed. Note, that most Credentials and DIDs are sharing the same context, which is the reason for many of the lines you actually see in the graph. (You can disable those lines explicitly in the filter settings, if you don't want to see JSON-LD Contexts Relationships)

## Controller
The Controller node represents the controller of a DID. The controller is the entity which is allowed to update the DID-Document. The controller is usually also the entity which created the DID. In case the controller is different you'll see the controller node.

## Credential Type
The Credential Type node represents the type of a Credential. The type is used to define the meaning of the Credential e.g. "OpenBadgeCredential" or "BachelorDegreeCredential".  
