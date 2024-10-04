# Credential Properties

The selection of either a Verifiable Credential (VC) or a Verifiable Presentation (VP) in the Graph View will display the properties of the selected entity on the right side of the screen. Depending on the type of entity and the resolution status, slightly different information is displayed.

## Verifiable Credential Properties
Similar to the DID-Properties, the properties of a Verifiable Credential are displayed in different sections:

### Credential-Identifier and Pool
Whereas a DID has a clear identifier (usually a DID), the identifier of a credential is often less helpful if present at all [Credential Identifiers Specification](https://www.w3.org/TR/vc-data-model/#identifiers). In case the Id is not present the type of the credential is displayed. To make make working with Credentials easier in the graph view a human readable name can be added to the credential.  You can also add tags to the credential or all other entities, which can be used to filter the graph. This is especially useful when you have a large dataset and want to focus on a specific subset of the data.

Below the name and tags, the pool is displayed, where the credential is stored. This is especially useful when you have multiple pools and want to know where the credential is located. Furthermore you find a direct link to the pool-manager, a tool to filter down the contents of the pool (*Might still be disabled in the published version*).

### Credential Content and Subject
The Credential Content section contains all the Credential-Metadata which is not part of the Subject. Most importantly it contains the Issuer and Issuance-Date and optionally the Expiration-Date of the Credential.
THe Subbject section contains all information related to the subject. This is usrually the Holder and the claims transmitted in the credential. e.g. the Bachelor-Degree for the specific subject. 

### Presentation Audience
While the Presentation mostly contains similar information as the Credential, the Audience is an important part of the Presentation. It shows for which receiver the Presentation was created and who is the intended audience.  