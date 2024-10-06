# BC-Org-Book

## VP 1
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://andrewwhitehead.github.io/anoncreds-w3c-mapping/schema.json"
  ],
  "type": [
    "VerifiablePresentation",
    "AnonCredsPresentation"
  ],
  "verifiableCredential": [
    {
      "@context": [
        "https://www.w3.org/2018/credentials/v1",
        "https://andrewwhitehead.github.io/anoncreds-w3c-mapping/schema.json",
        {
          "@vocab": "urn:anoncreds:attributes#"
        }
      ],
      "type": [
        "VerifiableCredential",
        "AnonCredsPresentation"
      ],
      "issuer": "did:indy:sovrin:HR6vs6GEZ8rHaVgjg2WodM",
      "issuanceDate": "2024-04-08T14:43:58Z",
      "credentialSchema": {
        "type": "AnonCredsDefinition",
        "id": "did:sov:HR6vs6GEZ8rHaVgjg2WodM:3:CL:41053:tag",
        "schema": "did:sov:HR6vs6GEZ8rHaVgjg2WodM:2:relationship.registries.ca:1.0.42"
      },
      "credentialSubject": {
        "id":"did:example:7ba36050-e29d-42a7-9b9d-c4dd4b9a7eb4",
        "associated_registration_name": "",
        "registration_id": "BC0843509",
        "effective_date": "2023-03-07T02:26:01.788262+00:00",
        "relationship_status": "ACT",
        "expiry_date": "",
        "relationship": "Owns",
        "relationship_status_effective": "2023-03-07T02:26:01.788262+00:00",
        "associated_registration_id": "FM1010836",
        "reason_description": "",
        "relationship_description": "Does Business As"
      },
      "proof": {
        "type": "AnonCredsPresentationProof2022",
        "credential": {
          "encoding": "auto",
          "index": 0,
          "mapping": {
            "revealedAttributes": {
              "self-verify-proof": [
                "associated_registration_name",
                "registration_id",
                "effective_date",
                "relationship_status",
                "expiry_date",
                "relationship",
                "relationship_status_effective",
                "associated_registration_id",
                "reason_description",
                "relationship_description"
              ]
            }
          },
          "eqProof": "AAEAGR3Ppb-Qutm3lAURBs5MRaQFDyz83iqcjCOSx32oZWPJWczNNax6MxGzdLSSVffBPlnyMtcUvZZnUH0v21wYwg8yHHZ__f_vfxQeshe_2dn6p3o3fjDmR6qmPOPVautgAXqzAOdjTaZURmovM00JL-EBkCpHafpV1Dx9WN5EtlwGUYMjSTVtdybLVL16hCD8tig10cmtDXdUQ0rWupJ1fUR5vxe8PrEGWNPyPFadMRTyktNWRZJLYz-l7lh4oHst2SzvnmNEpb0jwqBkhrBsrAG_lPdDeydE8rNVmiuCcE2g4yOWKN-vhXMY-UYXQgf7BVBANv2LuABJXzSeqElqbgEAObeKlLj_t6DnwovGFJgBhzNi4T_iOuB-PpF3bj7lcOhy0wW8Kw6dGI4xyOwk6qyt1jyuFRv3GMzHggIBfwU9h5MKTlCNOK2-5at47r5VPghnOdD6eb713goC-g04rV07C-eXvJZACybqV1dZwQaFWDHabTfeWSdHDLIDaA6JR-Xcsb2QHAJHOonLb5oUfdO76ZUZade1-wQZlqWUt0A7RB5T3wB-EbFzuH1CnR-HO4YvUvw-bpvJ6Le_CtCsm6rMcvNoe4-1n79OwIM6Jxctq4996ebbX5rS-qjiDhOWu0eJsDTF00Er2mZp2APFiUJYEle3kRHYYRRejhk221rMGvrHSi_O1pf7rwu0Vn09ZLt0pd8pZxB5l21wLmvcLUXoJ9M6Dpm0o3ndbvaKjrwsUn2OIpflWsqpMw354h50uVx51poTY1gZ-eBj8K3jVcFk9UNa6b_Xf-de1b_-1MtHZ2M6F3o6-vr7i7IfB86ERvfxw3towPRbyC0kbsVddv_bRk_YbfGJUGyZRYmSs-xNZd6YisR1SsrgodtCCYgIN2LSKtrRCk9Kg4sPdWOis--GAqkfDXFd9m2J7lW6AwBbAA1tYXN0ZXJfc2VjcmV0AEptCYlfc4F8UKhaDmk_0i_OpYvfyQsBJAZDBiRcIzQ5tow0HoPQ8n7VrcSS8tFf3cqWbj-W7RmCjwq5cPxxGuarP5N2kBZDk-39RgQASiceyZBEo04o-vM27YRL1guCJBo87p9u1fCxp_w21jt4AqaovVwXgYcX6TE3XAeOGJCh7knkTffauUVVH9lUSYB3S_yICXkXNQbS"
        }
      }
    }
  ],
  "proof": {
    "type": "AnonCredsPresentationProof2022",
    "nonce": "6458099187748906103206",
    "aggregated": "AAAg44sF6uZiFNvVvqFp8VlbPkYDtqyT18JwfLu8gaJKc5YBAQIBABkdz6W_kLrZt5QFEQbOTEWkBQ8s_N4qnIwjksd9qGVjyVnMzTWsejMRs3S0klX3wT5Z8jLXFL2WZ1B9L9tcGMIPMhx2f_3_738UHrIXv9nZ-qd6N34w5keqpjzj1WrrYAF6swDnY02mVEZqLzNNCS_hAZAqR2n6VdQ8fVjeRLZcBlGDI0k1bXcmy1S9eoQg_LYoNdHJrQ13VENK1rqSdX1Eeb8XvD6xBljT8jxWnTEU8pLTVkWSS2M_pe5YeKB7Ldks755jRKW9I8KgZIawbKwBv5T3Q3snRPKzVZorgnBNoOMjlijfr4VzGPlGF0IH-wVQQDb9i7gASV80nqhJam4"
  }
}

```

## VP 2
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://andrewwhitehead.github.io/anoncreds-w3c-mapping/schema.json"
  ],
  "type": [
    "VerifiablePresentation",
    "AnonCredsPresentation"
  ],
  "verifiableCredential": [
    {
      "@context": [
        "https://www.w3.org/2018/credentials/v1",
        "https://andrewwhitehead.github.io/anoncreds-w3c-mapping/schema.json",
        {
          "@vocab": "urn:anoncreds:attributes#"
        }
      ],
      "type": [
        "VerifiableCredential",
        "AnonCredsPresentation"
      ],
      "issuer": "did:indy:sovrin:HR6vs6GEZ8rHaVgjg2WodM",
      "issuanceDate": "2024-04-08T14:39:10Z",
      "credentialSchema": {
        "type": "AnonCredsDefinition",
        "id": "did:sov:HR6vs6GEZ8rHaVgjg2WodM:3:CL:41051:tag",
        "schema": "did:sov:HR6vs6GEZ8rHaVgjg2WodM:2:registration.registries.ca:1.0.42"
      },
      "credentialSubject": {
        "id":"did:example:800958fc-f9df-418e-903f-f93dcabb2c43",
        "entity_name": "ARTISAN GUIDE",
        "expiry_date": "",
        "entity_status_effective": "2023-03-06T18:26:01.788262+00:00",
        "home_jurisdiction": "BC",
        "registration_date": "2023-03-06T18:18:23.334202+00:00",
        "extra_jurisdictional_registration": "",
        "reason_description": "",
        "registered_jurisdiction": "BC",
        "entity_name_effective": "2023-03-06T18:26:01.788262+00:00",
        "entity_name_trans": "",
        "registration_id": "FM1010836",
        "entity_name_trans_effective": "",
        "effective_date": "2023-03-06T21:03:01.877003+00:00",
        "registration_renewal_effective": "",
        "registration_expiry_date": "",
        "entity_name_assumed_effective": "",
        "entity_status": "ACT",
        "entity_name_assumed": "",
        "entity_type": "SP"
      },
      "proof": {
        "type": "AnonCredsPresentationProof2022",
        "credential": {
          "encoding": "auto",
          "index": 0,
          "mapping": {
            "revealedAttributes": {
              "self-verify-proof": [
                "entity_name",
                "expiry_date",
                "entity_status_effective",
                "home_jurisdiction",
                "registration_date",
                "extra_jurisdictional_registration",
                "reason_description",
                "registered_jurisdiction",
                "entity_name_effective",
                "entity_name_trans",
                "registration_id",
                "entity_name_trans_effective",
                "effective_date",
                "registration_renewal_effective",
                "registration_expiry_date",
                "entity_name_assumed_effective",
                "entity_status",
                "entity_name_assumed",
                "entity_type"
              ]
            }
          },
          "eqProof": "AAEBAR7RRWSHCp2D8Lenjfub6qNvIhPivbWfTZwEKygUgwwx2Q0fHJf9mTdSUdGXrkXDWjIX55Kt5gEyHepdWi75m6EWafdlp5Hp1tltpYvvkIVSTxZYmp7QVB6J7d86mtvJ5jTp3q7j_XSZRn6co3fNHFH2X7JhAEXMs9OmWVdX9zcE8tz61rFyG1pDVd7zsQM8F5vnseA1WIEDHMptt8ACHrpzmIGke6zgUDy5lCv3PudrBuwsPTXcKQwWzSiReZWkJNxLKuku8GOojnJX0H4cRdoHz7vIEzCsXuqvU0vxB9zU-kVPaulLyub0VNiNiPFs-4jQf8x9acpZg1R8LbwpS84BADlSCACItvOxCMsM7ri43evHN7ZFxqL6xTHGVpsqZHEs6OA0GArUlBIIigTDxN1s67BJaWmet7-1-ysCAX8Bv11USpM28MQmDOypzIYJpKDn3oWQzVaTvqLyJprkEdS3Y55Rb44rVFbkriKzkBcbfssMyNL6OK1XPqxi-Rq_CdCHdJ3oQsZTv2qvYOBePVc6PRqGn9HBNvDezoZNcT8Kt-DwLoGuqdI8zrjw2GEqulMq18DxG2Ov_cfeKliwHKjj-NdLDk0SpG6-vB4wFgVxaDpFet3lQWzPa1nO7DC9_MlXjTOsFfDk9qhTZ91bCsXG5WnoQiyAhOltcu2dSvWk7gCXskGvPhUH9ehruuapO5puyNoXaSAvvd0vkSS-h8m8ugw0c9tiy9nJiITeHDGLjWTUHnItZH_GCGZEYlawa2PSaORuwELOtQIGdeB9IEbBbVjnFHlEuuWvKxWSL0b8LpUq3yLk2gUZbo74mDz-lmmbERg-7fWqhWeCc2HVtyhLhmokert6D9ubaEAkrhto_yu8GZFOn6O0TNCJzNgTi-UgNHYYeCZl1UH71KoNJf6uHzZRilrlYp8nlAThEAMAWwANbWFzdGVyX3NlY3JldABK6Ok5roDsmku_s-UI65wjDEC_sdrvqujfu0QmrZXiCQHI3tiB_o9qPNCUWi5AjZH14AhLBk4__OQS02721tr3lvhQw80jqiLkhxsEAEq-7ytZwJ9ynnPfy3UaZ8eb3g_f0sb8LB0ewAx2bh_AkK7dNAkaJRcWtFkGGsU83WPyRBryMZ-Kq4BHGf--Z5DBMPJwZ06fZR78yg"
        }
      }
    }
  ],
  "proof": {
    "type": "AnonCredsPresentationProof2022",
    "nonce": "687227550842710156307532",
    "aggregated": "AAAgoyJ5sP6rXhpDReQrnqrkbOtXRUcgYrPTsH7v61aAYIEBAQMBAQEe0UVkhwqdg_C3p437m-qjbyIT4r21n02cBCsoFIMMMdkNHxyX_Zk3UlHRl65Fw1oyF-eSreYBMh3qXVou-ZuhFmn3ZaeR6dbZbaWL75CFUk8WWJqe0FQeie3fOprbyeY06d6u4_10mUZ-nKN3zRxR9l-yYQBFzLPTpllXV_c3BPLc-taxchtaQ1Xe87EDPBeb57HgNViBAxzKbbfAAh66c5iBpHus4FA8uZQr9z7nawbsLD013CkMFs0okXmVpCTcSyrpLvBjqI5yV9B-HEXaB8-7yBMwrF7qr1NL8Qfc1PpFT2rpS8rm9FTYjYjxbPuI0H_MfWnKWYNUfC28KUvO"
  }
}

```

## VP 3
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://andrewwhitehead.github.io/anoncreds-w3c-mapping/schema.json"
  ],
  "type": [
    "VerifiablePresentation",
    "AnonCredsPresentation"
  ],
  "verifiableCredential": [
    {
      "@context": [
        "https://www.w3.org/2018/credentials/v1",
        "https://andrewwhitehead.github.io/anoncreds-w3c-mapping/schema.json",
        {
          "@vocab": "urn:anoncreds:attributes#"
        }
      ],
      "type": [
        "VerifiableCredential",
        "AnonCredsPresentation"
      ],
      "issuer": "did:indy:sovrin:HR6vs6GEZ8rHaVgjg2WodM",
      "issuanceDate": "2024-04-08T14:48:52Z",
      "credentialSchema": {
        "type": "AnonCredsDefinition",
        "id": "did:sov:HR6vs6GEZ8rHaVgjg2WodM:3:CL:54759:default",
        "schema": "did:sov:HR6vs6GEZ8rHaVgjg2WodM:2:business_number.registries.ca:1.0.42"
      },
      "credentialSubject": {
"id":"did:example:fc447aa4-30c0-40b5-abac-9a0b5f309c70",
        "business_number": "824421291",
        "expiry_date": "",
        "registration_id": "BC0843509",
        "effective_date": "2009-01-14T20:26:14+00:00",
        "reason_description": ""
      },
      "proof": {
        "type": "AnonCredsPresentationProof2022",
        "credential": {
          "encoding": "auto",
          "index": 0,
          "mapping": {
            "revealedAttributes": {
              "self-verify-proof": [
                "business_number",
                "expiry_date",
                "registration_id",
                "effective_date",
                "reason_description"
              ]
            }
          },
          "eqProof": "AAEBAQBAPQDybPft5QTyHP0AbpL-COrtb8pjw8UJAu012DU6fpJok4xODaW6TRa31ufEA5Lub7U_n7Lcdr795HWgR23HHIheiZqKl7FzrN2GYkN6XyXe8Y7TFp-XJJmvgpi6kUjqj2pPQbTjEMtjvXRT5fpitM9DDorYj-EBBkn_OQ94dRWR4T3NSHJQFsuBZKYY0BL-3hela4hRweDuAhWSY2-o6B_Ja-LRxvw97J4YgeD6z3N1VPOxTbNVBWVNfcUIdwCDfzphE-hqtyRXpEFs8EWAOxJi2Sgwqs4E4qJvZTy7xemEOfUqpk-qIWUrPnuuK_UrnK49Qpktp6-XHZNshjoBADmU3pPJC4aHgIOLAj5HrXyO8WXLxgRlH3Y0NiB4M2oNHrvUI9JzgyM2ySXHK32vFGj5NcRpr2cgt6sCAX8LPpx8Aa3Tt2tsKuJ1efKm8SSadpAFJV8cUh0SazHkIc5TXDrXM0Fp11JZ3fz6JNIF1GMVDpu3uNcQ7FZiHIUMJf7Z69E_GmvuO-9HdtmZB-QCrMVhm8jmAWdp5hAHU5FdaNIkQ_j7JRYXby6RUOSyVVI-6VnPY6VkHqwcWqkKQdbcNdrVXav5Vvxjny5OrA0I7BPeWdq5abYVB-nO6xXsfLkH-Y-uA_jt22l9di-Zw2QbjJsIj3FUEqRJ9lNw3g_tcaYS_8qG4Qi8TlOmI3c6xNBOH-EYZoCe8w8A0MHpws5zSKClVrwD8iyFlj1WKHkjqj5Q5KwqwqqvcpQlNah-Nqh_uBmuWGvbbUpqGDp3iipXv6D2OrHBNU7OGnYC-wc0gJGUwX_WYSDRiagohdaOZTZmVHu_4WpK-2GT40n6czmf3W4JI30PU6kxGmGGl8zSjwunQWqWiE_LdY5e_yKj6TB0OGdGJBdx-JLL2go96UlSIUltQ07941tBen96oAMAWwANbWFzdGVyX3NlY3JldABKdng1vsSPIInFAz4Y9kZS9r7dy6sm8xtu8xSbR6-GZlWcOz41MojPxtIWw8kpE_sQ-4x53f0p_htwepqmyb5zouhDXsgf62pkB-kEAErnb1rcUagfMt38XlgzXphVsZxhoSbClSKhjMHGZ1_EAcMcqfHenHgcelpyjOkkplf-CxE9_OsgBNd3Eu57VrcV4Yh3rbl7V5M3Kw"
        }
      }
    }
  ],
  "proof": {
    "type": "AnonCredsPresentationProof2022",
    "nonce": "868898228546451514651446",
    "aggregated": "AAAgfFg2hgtpXGUfsJ_y6kknSKLH_i1Aa5ykrxdI-Ht8TrwBAQMBAQEAQD0A8mz37eUE8hz9AG6S_gjq7W_KY8PFCQLtNdg1On6SaJOMTg2luk0Wt9bnxAOS7m-1P5-y3Ha-_eR1oEdtxxyIXomaipexc6zdhmJDel8l3vGO0xaflySZr4KYupFI6o9qT0G04xDLY710U-X6YrTPQw6K2I_hAQZJ_zkPeHUVkeE9zUhyUBbLgWSmGNAS_t4XpWuIUcHg7gIVkmNvqOgfyWvi0cb8PeyeGIHg-s9zdVTzsU2zVQVlTX3FCHcAg386YRPoarckV6RBbPBFgDsSYtkoMKrOBOKib2U8u8XphDn1KqZPqiFlKz57riv1K5yuPUKZLaevlx2TbIY6"
  }
}

```