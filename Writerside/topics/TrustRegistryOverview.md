# Trust Registry Management

Trust registries are systems used to assess the trustworthiness of Verifiable Credentials by verifying not only the cryptographic signatures and proofs but also the authority of the credential's issuer. This specification establishes the roles and authority of participants within an ecosystem to address the fundamental question: "Should I trust the issuer of this credential?"

The specification is created, signed, and published by an ecosystem authority, which gains its authority through recognition by ecosystem participants via agreement, contract, law, or other methods. The information within the published document allows for the identification and evaluation of credential issuers. This format is lightweight, supports both large and small ecosystems, enables offline verification, and is low cost. It incorporates the Trust Establishment specification for listing ecosystem participants.

The data model represents the trust expressions from the ecosystem authority. The authority carefully selects the information in the document, including schemas, participants, and governance files. While the file informs ecosystem participants of the publisher's opinions, it does not obligate them to follow or respect these opinions. Participants may selectively respect parts of the published governance, influenced by ecosystem factors outside the scope of this format.

In the current implementation the only supported type of Trust Registries is the *Credential Trust Establishment* Specification, developed under the *DIF* [Credential Trust Establishment Working Group](https://identity.foundation/credential-trust-establishment/).

To use Trust Registries within the *Analytics Platform*, first create a Trust Registry on the Tenant Overview page and then link it when creating a new session. The software will automatically query the Trust Registry and display the connections in the Graph if a suitable DID is used in the Graph.


