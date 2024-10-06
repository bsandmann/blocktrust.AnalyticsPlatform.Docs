# Travelling with minor

## Anands Passport
```json
{
  "@context": [
    "https://w3id.org/credentials/v1",
    "https://example.com/travel-vocab/v1"
  ],
  "id": "urn:uuid:05a47fe2-73c8-11e8-ac1e-7fe0051a1d75",
  "type": ["VerifiableCredential", "BirthCertificate"],
  "issuer": "did:prism:preprod:59fb983e7dd24e3e051d1786f0b934bffd8838f26fe338df86545a19381903a4",
  "expires": "2020-01-01T00:00:00Z",
  "credentialSubject": {
    "id": "did:example:8vFBbPrhBUyG6DEzVncBZpzBNsmRrbfsQKXQKPLskBCu",
    "citizenship": "US",
    "birthDate": "2017-10-01T00:00:00Z",
    "birthPlace": {
      "type": "Hospital",
      "address": {
        "type": "US address",
        "addressLocality": "Denver",
        "addressRegion": "CO",
        "postalCode": "80209",
        "streetAddress": "123 Main St."
      }
    },
    "givenName": "Anand",
    "familyName": "Hamal",
    "parent": [{
      "id": "did:example:BcRisGnqV4QPb6bRmDCqEjyuubBarS1Y1nhDwxBMTXY4",
      "type": "Person",
      "givenName": "Malathi",
      "familyName": "Hamal",
      "maidenName": "Holla"
    }, {
      "id": "did:example:BgXRjB4RPrrsUVoVNaYNwzfznKsWep7AWrZkiyVcorEN",
      "type": "Person",
      "givenName": "Rajesh",
      "familyName": "Hamal"
    }]
  },
  "proof": {"proof by": "the government"}
}
```

## Malathis Passport
```json
{
  "@context": [
    "https://w3id.org/credentials/v1",
    "https://example.com/travel-vocab/v1"
  ],
  "id": "urn:uuid:9f6878c8-73c7-11e8-ab37-23a1a3504fd0",
  "type": ["VerifiableCredential", "PassportCredential"],
  "issuer": "did:prism:preprod:59fb983e7dd24e3e051d1786f0b934bffd8838f26fe338df86545a19381903a4",
  "expires": "2028-01-01T00:00:00Z",
  "credentialSubject": {
    "id": "did:example:BcRisGnqV4QPb6bRmDCqEjyuubBarS1Y1nhDwxBMTXY4",
    "passport": {
      "id": "urn:uuid:79c181dc-73c7-11e8-8c1f-2bb1fd2d268a",
      "type": "Passport",
      "traveler": {
        "id": "did:example:BcRisGnqV4QPb6bRmDCqEjyuubBarS1Y1nhDwxBMTXY4",
        "givenName": "Malathi",
        "familyName": "Hamal",
        "citizenship": "US"
      }
    }
  },
  "proof": {"proof by": "the government"}
}
```

## Permission
```json
{
  "@context": [
    "https://w3id.org/credentials/v1",
    "https://example.com/travel-vocab/v1"
  ],
  "id": "urn:uuid:58c08196-73c6-11e8-b030-3bd8a829a356",
  "type": ["VerifiableCredential", "ChildTravelPass"],
  "issuer": "did:prism:preprod:937b4fd4e9700d99fa4df9f9f568790f3033468b612b6bfc0f788a2fe36195f2",
  "expires": "2018-07-01T00:00:00Z",
  "credentialSubject": {
    "id": "did:example:8vFBbPrhBUyG6DEzVncBZpzBNsmRrbfsQKXQKPLskBCu",
    "potentialAction": {
      "type": "TravelAction",
      "agent": "did:example:8vFBbPrhBUyG6DEzVncBZpzBNsmRrbfsQKXQKPLskBCu",
      "participant": "did:example:BcRisGnqV4QPb6bRmDCqEjyuubBarS1Y1nhDwxBMTXY4",
      "location": {
        "type": "Country",
        "address": {
          "addressCountry": "CA"
        }
      }
    }
  },
  "proof": {"signature": "from the mother"}
}
```