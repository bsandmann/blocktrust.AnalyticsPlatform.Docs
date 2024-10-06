# Traceability

## Commercial Invoive
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1"
  ],
  "id": "urn:uuid:5e45f155-c949-4005-a7e5-26ni58b6a59a",
  "type": [
    "VerifiableCredential",
    "CommercialInvoiceCredential"
  ],
  "issuanceDate": "2022-02-23T11:55:00Z",
  "issuer": {
    "type": [
      "Organization"
    ],
    "id": "did:example:quality-metals.example.com",
    "name": "Aishi Metal Shinzo Co., Ltd.",
    "location": {
      "type": [
        "Place"
      ],
      "address": {
        "type": [
          "PostalAddress"
        ],
        "streetAddress": "1651, Shimonakano, Yoshida",
        "addressLocality": "Tsubame-shi",
        "addressRegion": "Niigata-ken",
        "postalCode": "959-0215",
        "addressCountry": "Japan"
      }
    }
  },
  "credentialSubject": {
    "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
    "type": [
      "Invoice"
    ],
    "portOfEntry": {
      "type": [
        "Place"
      ],
      "unLocode": "USLGB"
    },
    "invoiceNumber": "INV-1000288",
    "purchaseOrderNumbers": [
      "PO992765413"
    ],
    "destinationCountry": "MX",
    "purchaseDate": "2021-02-21",
    "seller": {
      "type": [
        "Organization"
      ],
      "name": "Aishi Metal Shinzo Co., Ltd.",
      "location": {
        "type": [
          "Place"
        ],
        "address": {
          "type": [
            "PostalAddress"
          ],
          "streetAddress": "1651, Shimonakano, Yoshida",
          "addressLocality": "Tsubame-shi",
          "addressRegion": "Niigata-ken",
          "postalCode": "959-0215",
          "addressCountry": "Japan"
        }
      }
    },
    "buyer": {
      "type": [
        "Organization"
      ],
      "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
      "name": "Generic Motors of America",
      "location": {
        "type": [
          "Place"
        ],
        "address": {
          "type": [
            "PostalAddress"
          ],
          "streetAddress": "12 Generic Motors Dr",
          "addressLocality": "Detroit",
          "addressRegion": "Michigan",
          "postalCode": "48232-5170",
          "addressCountry": "US"
        }
      }
    },
    "consignee": [
      {
        "type": [
          "Organization"
        ],
        "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
        "name": "Generic Motors of America",
        "location": {
          "type": [
            "Place"
          ],
          "address": {
            "type": [
              "PostalAddress"
            ],
            "streetAddress": "12 Generic Motors Dr",
            "addressLocality": "Detroit",
            "addressRegion": "Michigan",
            "postalCode": "48232-5170",
            "addressCountry": "US"
          }
        }
      }
    ],
    "itemsShipped": [
      {
        "type": [
          "TradeLineItem"
        ],
        "product": {
          "type": [
            "Product"
          ],
          "manufacturer": {
            "type": [
              "Organization"
            ],
            "name": "Maxi Acero Mexicano"
          },
          "description": "UNS S30400 chromium-nickel stainless steel rolls.",
          "weight": {
            "type": [
              "QuantitativeValue"
            ],
            "unitCode": "lbs",
            "value": "16500"
          }
        },
        "itemCount": 5,
        "grossWeight": {
          "type": [
            "QuantitativeValue"
          ],
          "value": "82500",
          "unitCode": "lbs"
        },
        "lineItemTotalPrice": {
          "type": [
            "PriceSpecification"
          ],
          "price": 5200,
          "priceCurrency": "USD"
        }
      },
      {
        "type": [
          "TradeLineItem"
        ],
        "product": {
          "type": [
            "Product"
          ],
          "manufacturer": {
            "type": [
              "Organization"
            ],
            "name": "Maxi Acero Mexicano"
          },
          "description": "Galvalannealed ASTM A-653 zinc-iron alloy-coated steel sheets.",
          "weight": {
            "type": [
              "QuantitativeValue"
            ],
            "value": "12680",
            "unitCode": "lbs"
          }
        },
        "itemCount": 20,
        "grossWeight": {
          "type": [
            "QuantitativeValue"
          ],
          "value": "253600",
          "unitCode": "lbs"
        },
        "lineItemTotalPrice": {
          "type": [
            "PriceSpecification"
          ],
          "price": 4400,
          "priceCurrency": "USD"
        }
      }
    ],
    "totalWeight": {
      "type": [
        "QuantitativeValue"
      ],
      "value": "336100",
      "unitCode": "lbs"
    },
    "totalPaymentDue": {
      "type": [
        "PriceSpecification"
      ],
      "price": 9600,
      "priceCurrency": "USD"
    }
  }
}
```

## CTPAT
```json
{
  "type": [
    "VerifiableCredential",
    "CTPATCertificate"
  ],
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1",
    "https://w3id.org/vc/status-list/2021/v1"
  ],
  "id": "urn:uuid:2385e117-8011-4n15-bcae-64e4e26856c8",
  "name": "CTPAT Certificate",
  "description": "In recognition of your commitment to partnership, and in appreciation for joining with us to secure the international supply chain and protect our country's security, the U.S. Customs Service is pleased to certify your membership in the Customs - Trade Partnership Against Terrorism.",
  "issuer": {
    "type": [
      "Organization"
    ],
    "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
    "name": "Customs Trade Partnership Against Terrorism"
  },
  "issuanceDate": "2022-01-13T09:16:46Z",
  "expirationDate": "2059-01-13T09:16:46Z",
  "credentialSubject": {
    "type": [
      "CTPAT"
    ],
    "id": "did:example:quality-metals.example.com",
    "member": {
      "type": [
        "CTPATMember"
      ],
      "name": "Quality Metals Inc",
      "id": "did:example:quality-metals.example.com",
      "importerOfRecord": {
        "type": [
          "CBPImporterOfRecord"
        ],
        "number": "10025672",
        "identifierType": "CBP"
      },
      "scac": "NISC",
      "iataCarrierCode": "ABZ",
      "fmcNumber": "025202",
      "filerCode": "HX3",
      "ibanNumber": "DK9520000123456789",
      "duns": "782011415",
      "url": "https://quality-metals.example.com",
      "faxNumber": "+1-628-555-9153",
      "location": [
        {
          "type": [
            "Place"
          ],
          "address": {
            "type": [
              "PostalAddress"
            ],
            "name": "Quality Metals",
            "streetAddress": "1040 Newland Drive",
            "addressLocality": "Yellowville",
            "addressRegion": "Texas",
            "postalCode": "28101",
            "addressCountry": "US"
          }
        }
      ]
    },
    "sviNumber": "57118961",
    "ctpatAccountNumber": "12008",
    "tradeSector": "Sea Carrier",
    "tier": "Certified",
    "dateOfLastValidation": "2022-01-06T11:50:00Z",
    "issuingCountry": "US"
  },
  "credentialStatus": {
    "id": "https://api.did.actor/revocation-lists/1.json#0",
    "type": "RevocationList2020Status",
    "revocationListIndex": 0,
    "revocationListCredential": "https://api.did.actor/revocation-lists/1.json"
  }
}
```

## Entry Number
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1"
  ],
  "id": "http://example.com/dd0c6f9a-5df6-40a3-bb34-863cd1fda606",
  "type": [
    "VerifiableCredential",
    "EntryNumberCredential"
  ],
  "issuer": {
    "type": [
      "Organization"
    ],
    "id": "did:example:o376CuiTpBmyMWfRRohk44dsz6MktHQbEaBSeE3Uq2VVjvV6",
    "name": "Onwards A/S",
    "location": {
      "type": [
        "Place"
      ],
      "address": {
        "type": [
          "PostalAddress"
        ],
        "streetAddress": "19 Knox St",
        "addressLocality": "Toronto",
        "addressRegion": "ON",
        "addressCountry": "CA",
        "postalCode": "M3B 1A2"
      }
    }
  },
  "issuanceDate": "2022-11-01T10:58:45-04:00",
  "credentialSubject": {
    "id": "did:example:o376CuiTpBmyMWfRRohk44dsz6MktHQbEaBSeE3Uq2VVjvV6",
    "type": [
      "EntryNumber"
    ],
    "entryNumber": "12345123456"
  }
}
```

## Intent to Import
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1"
  ],
  "id": "urn:uuid:55791fb7-058f-409a-8a32-e6229n159144",
  "type": [
    "VerifiableCredential",
    "IntentToImportCredential"
  ],
  "issuer": {
    "type": [
      "Organization"
    ],
    "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
    "name": "Generic Motors of America",
    "location": {
      "type": [
        "Place"
      ],
      "address": {
        "type": [
          "PostalAddress"
        ],
        "streetAddress": "12 Generic Motors Dr",
        "addressLocality": "Detroit",
        "addressRegion": "Michigan",
        "postalCode": "48232-5170",
        "addressCountry": "US"
      }
    }
  },
  "issuanceDate": "2022-03-03T15:20:00Z",
  "credentialSubject": {
    "type": [
      "IntentToImport"
    ],
    "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
    "importIntent": "By issuing this Intent to Import Verifiable Credential and presenting it in a Traceable Presentation to US CBP, the issuing organization initiates a digital procedure for importing goods into the United States."
  }
}
```

## Mill Test Report
```json

{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1"
  ],
  "type": [
    "VerifiableCredential",
    "MillTestReportCredential"
  ],
  "id": "urn:uuid:2e604860-b308-4ada-n1s3-4a22635befea",
  "issuer": {
    "type": [
      "Organization"
    ],
    "id": "did:example:RRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeEasdfasdf33a",
    "name": "Tall Steel, Inc",
    "location": {
      "type": [
        "Place"
      ],
      "address": {
        "type": [
          "PostalAddress"
        ],
        "streetAddress": "1331 N 7th St",
        "addressLocality": "Phoenix",
        "addressRegion": "Arizona",
        "postalCode": "78599",
        "addressCountry": "US"
      }
    },
    "phoneNumber": "+1-675-555-6659",
    "faxNumber": "+1-527-555-1986"
  },
  "issuanceDate": "2022-06-06T08:10:00+00:00",
  "credentialSubject": {
    "id": "did:example:quality-metals.example.com",
    "certificateNumber": "202304215088",
    "certification": "EN 10204.3.1",
    "purchaseOrderNumber": "PO992765413",
    "meansOfTransport": "Road",
    "customer": {
      "type": [
        "Organization"
      ],
      "id": "did:web:rise-higher-construction.example.com",
      "name": "Rise Higher Construction, Ltd.",
      "location": {
        "type": [
          "Place"
        ],
        "address": {
          "type": [
            "PostalAddress"
          ],
          "plantOrSiteName": "Rise Warehouse West",
          "streetAddress": "4423 Reeves Street",
          "addressLocality": "Baileys Harbor",
          "addressRegion": "California",
          "postalCode": "98200",
          "addressCountry": "US"
        }
      }
    },
    "productSpecification": {
      "type": [
        "SteelProduct"
      ],
      "standard": "AISI/SAE",
      "grade": "316",
      "heatTreatment": "Min. 1900F, Quenched",
      "surfaceTreatment": "Varnished",
      "productDescription": "Stainless Steel Plate"
    },
    "remarks": "No Mercury, Lead or Sulfor. Free from radioactive contamination.",
    "inspections": [
      {
        "type": [
          "Inspection"
        ],
        "productIdentifier": "212900-34",
        "productDimensions": {
          "type": [
            "ProductDimensions"
          ],
          "length": {
            "type": [
              "MeasuredValue"
            ],
            "value": "6000",
            "unitCode": "MM"
          },
          "width": {
            "type": [
              "MeasuredValue"
            ],
            "value": "2000",
            "unitCode": "MM"
          },
          "thickness": {
            "type": [
              "MeasuredValue"
            ],
            "value": "60",
            "unitCode": "MM"
          }
        },
        "pieces": 80,
        "perUnitWeight": {
          "type": [
            "MeasuredValue"
          ],
          "value": "3620",
          "unitCode": "KG"
        },
        "totalWeight": {
          "type": [
            "MeasuredValue"
          ],
          "value": "289600",
          "unitCode": "KG"
        },
        "countryOfManufacture": "US",
        "countryOfMeltAndPour": "US",
        "meltPractice": "EAM",
        "heatNumber": "61316",
        "testNumber": "1205",
        "chemicalComposition": {
          "type": [
            "ChemicalComposition"
          ],
          "c": 0.0189,
          "mn": 1.568,
          "p": 0.035,
          "s": 0.0128,
          "si": 0.312,
          "al": 0.004,
          "cu": 0.4208,
          "ni": 8.286,
          "cr": 16.558,
          "mo": 2.03,
          "sn": 0.007,
          "nbCb": 0,
          "v": 0.004,
          "ti": 0.003,
          "b": 0.0014,
          "n": 0.0074,
          "ca": 0.0018,
          "pb": 0.001,
          "ce": 0.3882
        },
        "mechanicalProperties": {
          "type": [
            "MechanicalProperties"
          ],
          "tensile": {
            "type": [
              "MeasuredValue"
            ],
            "value": "367.22",
            "unitCode": "MPa"
          },
          "yield": {
            "type": [
              "MeasuredValue"
            ],
            "value": "648.71",
            "unitCode": "MPa"
          },
          "hardness": {
            "type": [
              "MeasuredValue"
            ],
            "value": "86",
            "unitCode": "HRB"
          },
          "elongation": {
            "type": [
              "MeasuredValue"
            ],
            "value": "32",
            "unitCode": "%"
          },
          "charpy": {
            "type": [
              "MeasuredValue"
            ],
            "value": "3.55",
            "unitCode": "J"
          },
          "reduction": {
            "type": [
              "MeasuredValue"
            ],
            "value": "40",
            "unitCode": "%"
          }
        }
      }
    ]
  }
}
```

## Multi Model Bill of Lading
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1"
  ],
  "id": "did:key:z6MkmbqKc6KncFZUbVJwUppttTkiMAtnVJ5wzC5oVBWci3pc",
  "type": [
    "VerifiableCredential",
    "MultiModalBillOfLadingCredential"
  ],
  "issuanceDate": "2022-03-04T13:40:00Z",
  "issuer": {
    "type": [
      "Organization"
    ],
    "id": "did:key:BmyMWq2Vz6MkE3UtHQo3fRRohk44dsbE76CuiTpVjvV6aBSe",
    "name": "MULTI CONTAINER LINE",
    "scac": "MCLI",
    "location": {
      "type": [
        "Place"
      ],
      "address": {
        "type": [
          "PostalAddress"
        ],
        "name": "MCL Multi Container Line LTD.",
        "streetAddress": "Rm. 3501, 35/F Manhatten Place, 23 Wang Tai Road",
        "addressLocality": "Kowloon Bay",
        "addressRegion": "Hong Kong",
        "addressCountry": "HK"
      }
    }
  },
  "credentialSubject": {
    "type": [
      "MultiModalBillOfLading"
    ],
    "billOfLadingNumber": "EX600822199A",
    "bookingNumber": [
      "EX600822199"
    ],
    "shipper": {
      "type": [
        "Organization"
      ],
      "name": "Espresso Italiano Co.",
      "location": {
        "type": [
          "Place"
        ],
        "address": {
          "type": [
            "PostalAddress"
          ],
          "streetAddress": "Via Vico Ferrovia 5",
          "addressLocality": "Goro",
          "addressRegion": "Ferrara",
          "postalCode": "44020",
          "addressCountry": "IT"
        }
      },
      "email": "sales@espresso-italiano.example.com",
      "phoneNumber": "+39 5555 5252682"
    },
    "mainCarriageTransportMovement": {
      "type": [
        "Transport"
      ],
      "vesselNumber": "MS Seven Seas",
      "voyageNumber": "Atl-W0425"
    },
    "portOfLoading": {
      "type": [
        "Place"
      ],
      "unLocode": "ITMIL"
    },
    "portOfDischarge": {
      "type": [
        "Place"
      ],
      "unLocode": "USLGB"
    },
    "totalNumberOfPackages": 2200,
    "transportEquipmentQuantity": 2,
    "utilizedTransportEquipment": [
      {
        "type": [
          "TransportEquipment"
        ],
        "equipmentReference": "APZU4812090",
        "ISOEquipmentCode": "40GP",
        "seals": [
          {
            "type": [
              "Seal"
            ],
            "sealNumber": "PTW-002290109692"
          }
        ]
      },
      {
        "type": [
          "TransportEquipment"
        ],
        "equipmentReference": "APZU5985096",
        "ISOEquipmentCode": "40GP",
        "seals": [
          {
            "type": [
              "Seal"
            ],
            "sealNumber": "PTW-002255398220"
          }
        ]
      }
    ],
    "particulars": [
      {
        "type": [
          "ConsignmentItem"
        ],
        "marksAndNumbers": "Espresso Italiano",
        "commodity": {
          "type": [
            "Commodity"
          ],
          "commodityCode": "8516.71",
          "commodityCodeType": "HS"
        },
        "packageQuantity": 2200,
        "netWeight": {
          "type": [
            "QuantitativeValue"
          ],
          "unitCode": "kg",
          "value": "14600"
        },
        "grossWeight": {
          "type": [
            "QuantitativeValue"
          ],
          "unitCode": "kg",
          "value": "15960"
        },
        "grossVolume": {
          "type": [
            "QuantitativeValue"
          ],
          "value": "220",
          "unitCode": "cmb"
        }
      }
    ],
    "freightAndCharges": [
      {
        "type": [
          "ServiceCharge"
        ],
        "chargeCode": "basicFreight",
        "paymentTerm": "collect",
        "chargeText": "Negotiated ocean freight",
        "rate": {
          "type": [
            "PriceSpecification"
          ],
          "price": 2250,
          "priceCurrency": "USD"
        },
        "calculationBasis": "Per container",
        "appliedAmount": {
          "type": [
            "PriceSpecification"
          ],
          "price": 4500,
          "priceCurrency": "USD"
        }
      }
    ],
    "declaredValue": {
      "type": [
        "PriceSpecification"
      ],
      "price": 240000,
      "priceCurrency": "USD"
    },
    "shippedOnBoardDate": "2022-02-02",
    "termsAndConditions": "https://terms-of-shipment.carrier.example.com"
  }
}
```

## Purchase Order
```json

{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1"
  ],
  "id": "https://example.com/credential/123",
  "type": [
    "VerifiableCredential",
    "PurchaseOrderCredential"
  ],
  "issuanceDate": "2019-12-11T03:50:55Z",
  "issuer": {
    "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
    "type": [
      "Organization"
    ],
    "name": "Generic Motors of America",
    "location": {
      "type": [
        "Place"
      ],
      "address": {
        "type": [
          "PostalAddress"
        ],
        "streetAddress": "12 Generic Motors Dr",
        "addressLocality": "Detroit",
        "addressRegion": "Michigain",
        "postalCode": "48232-5170",
        "addressCountry": "USA"
      }
    }
  },
  "credentialSubject": [
    {
      "type": [
        "PurchaseOrder"
      ],
      "id": "did:example:z6MktHQo3fRRohk44dsbE76CuiTpBmyMWq2VVjvV6aBSeE3U",
      "purchaseOrderNo": "fe71665a-e7b3-49ba-ac89-82fc2bf1e877",
      "orderDate": "2021-02-21",
      "buyer": {
        "type": [
          "Organization"
        ],
        "name": "Generic Motors of America",
        "location": {
          "type": [
            "Place"
          ],
          "address": {
            "type": [
              "PostalAddress"
            ],
            "streetAddress": "12 Generic Motors Dr",
            "addressLocality": "Detroit",
            "addressRegion": "Michigain",
            "postalCode": "48232-5170",
            "addressCountry": "USA"
          }
        }
      },
      "items": [
        {
          "type": [
            "TradeLineItem"
          ],
          "product": {
            "type": [
              "Product"
            ],
            "id": "https://aishi-metal-shinzo.example.com/products/UNS-S30400-chromium-nickel-stainless-steel-roll",
            "description": "UNS S30400 chromium-nickel stainless steel roll",
            "weight": {
              "type": [
                "QuantitativeValue"
              ],
              "unitCode": "lbs",
              "value": "16500"
            }
          },
          "itemCount": 5,
          "grossWeight": {
            "type": [
              "QuantitativeValue"
            ],
            "value": "82500",
            "unitCode": "lbs"
          },
          "lineItemTotalPrice": {
            "type": [
              "PriceSpecification"
            ],
            "price": 5200,
            "priceCurrency": "USD"
          }
        },
        {
          "type": [
            "TradeLineItem"
          ],
          "product": {
            "type": [
              "Product"
            ],
            "id": "https://aishi-metal-shinzo.example.com/products/Galvannealed-ASTM-A-653-zinc-iron-alloy-coated-steel-sheet",
            "description": "Galvalannealed ASTM A-653 zinc-iron alloy-coated steel sheet",
            "weight": {
              "type": [
                "QuantitativeValue"
              ],
              "value": "12680",
              "unitCode": "lbs"
            }
          },
          "itemCount": 20,
          "grossWeight": {
            "type": [
              "QuantitativeValue"
            ],
            "value": "253600",
            "unitCode": "lbs"
          },
          "lineItemTotalPrice": {
            "type": [
              "PriceSpecification"
            ],
            "price": 4400,
            "priceCurrency": "USD"
          }
        }
      ],
      "totalWeight": {
        "type": [
          "QuantitativeValue"
        ],
        "value": "336100",
        "unitCode": "lbs"
      },
      "totalOrderAmount": {
        "type": [
          "PriceSpecification"
        ],
        "price": 9600,
        "priceCurrency": "USD"
      }
    },
    {
        "type": [
      "PurchaseOrder"
    ],
    "id": "did:example:quality-metals.example.com",
    "purchaseOrderNo": "fe71665a-e7b3-49ba-ac89-82fc2bf1e877",
    "orderDate": "2021-02-21",
    "seller": {
      "type": [
        "Organization"
      ],
      "name": "Aishi Metal Shinzo Co., Ltd.",
      "location": {
        "type": [
          "Place"
        ],
        "address": {
          "type": [
            "PostalAddress"
          ],
          "streetAddress": "1651, Shimonakano, Yoshida",
          "addressLocality": "Tsubame-shi",
          "addressRegion": "Niigata-ken",
          "postalCode": "959-0215",
          "addressCountry": "Japan"
        }
      }
    },
    "items": [
      {
        "type": [
          "TradeLineItem"
        ],
        "product": {
          "type": [
            "Product"
          ],
          "id": "https://aishi-metal-shinzo.example.com/products/UNS-S30400-chromium-nickel-stainless-steel-roll",
          "description": "UNS S30400 chromium-nickel stainless steel roll",
          "weight": {
            "type": [
              "QuantitativeValue"
            ],
            "unitCode": "lbs",
            "value": "16500"
          }
        },
        "itemCount": 5,
        "grossWeight": {
          "type": [
            "QuantitativeValue"
          ],
          "value": "82500",
          "unitCode": "lbs"
        },
        "lineItemTotalPrice": {
          "type": [
            "PriceSpecification"
          ],
          "price": 5200,
          "priceCurrency": "USD"
        }
      },
      {
        "type": [
          "TradeLineItem"
        ],
        "product": {
          "type": [
            "Product"
          ],
          "id": "https://aishi-metal-shinzo.example.com/products/Galvannealed-ASTM-A-653-zinc-iron-alloy-coated-steel-sheet",
          "description": "Galvalannealed ASTM A-653 zinc-iron alloy-coated steel sheet",
          "weight": {
            "type": [
              "QuantitativeValue"
            ],
            "value": "12680",
            "unitCode": "lbs"
          }
        },
        "itemCount": 20,
        "grossWeight": {
          "type": [
            "QuantitativeValue"
          ],
          "value": "253600",
          "unitCode": "lbs"
        },
        "lineItemTotalPrice": {
          "type": [
            "PriceSpecification"
          ],
          "price": 4400,
          "priceCurrency": "USD"
        }
      }
    ],
    "totalWeight": {
      "type": [
        "QuantitativeValue"
      ],
      "value": "336100",
      "unitCode": "lbs"
    },
    "totalOrderAmount": {
      "type": [
        "PriceSpecification"
      ],
      "price": 9600,
      "priceCurrency": "USD"
    }
  }
    ]
}
```

## SIMA Import License 
```json
{
  "@context": [
    "https://www.w3.org/2018/credentials/v1",
    "https://w3id.org/traceability/v1"
  ],
  "id": "urn:uuid:2c9f4c3d-0874-44ce-a3a8-617e55454fc1",
  "type": [
    "VerifiableCredential",
    "SIMASteelImportLicenseCredential"
  ],
  "issuer": {
    "type": [
      "Organization"
    ],
    "id": "did:example:E76CuiTpBmyMWq2VVjvz6MktHQsbV6aBSeE3Uo3fRRohk44d",
    "name": "US Steel Import Monitoring and Analysis (SIMA)"
  },
  "issuanceDate": "2023-02-28T11:23:00Z",
  "expirationDate": "2024-02-28T11:23:00Z",
  "credentialSubject": {
    "type": [
      "SIMASteelImportLicense"
    ],
    "id": "did:example:quality-metals.example.com",
    "customsEntryNumber": "34001239",
    "licensedCompany": {
      "type": [
        "Organization"
      ],
      "id": "did:example:quality-metals.example.com",
      "name": "Maxi Acero Mexicano",
      "location": {
        "type": [
          "Place"
        ],
        "address": {
          "type": [
            "PostalAddress"
          ],
          "streetAddress": "Avenida Carlos 100",
          "addressLocality": "Hernádez de Mara",
          "addressRegion": "Nuevo Leon",
          "postalCode": "32200",
          "addressCountry": "Mexico"
        }
      }
    },
    "importer": {
      "type": [
        "Organization"
      ],
      "name": "American Prime Steel Inc."
    },
    "exporter": {
      "type": [
        "Organization"
      ],
      "name": "Maxi Acero Mexicano"
    },
    "manufacturer": {
      "type": [
        "Organization"
      ],
      "name": "Maxi Acero Mexicano"
    },
    "countryOfOrigin": "MX",
    "countryOfExportation": "MX",
    "expectedPortOfEntry": "USMOB",
    "expectedDateOfExport": "2022-04-02T08:00:00Z",
    "expectedDateOfImport": "2022-04-09T10:30:00Z",
    "productInformation": [
      {
        "type": [
          "SIMASteelImportProductSpecifier"
        ],
        "commodity": {
          "type": [
            "Commodity"
          ],
          "commodityCode": "7207200075",
          "commodityCodeType": "HTS",
          "description": "SEMIFINISHED IRON/NONALLOW STL"
        },
        "productCategory": "Blooms, Billets and Slabs",
        "countryOfMeltAndPour": "AR",
        "weight": {
          "type": [
            "MeasuredValue"
          ],
          "value": "10000",
          "unitCode": "KGM"
        },
        "customsValue": {
          "type": [
            "MonetaryAmount"
          ],
          "value": 24000,
          "currency": "USD"
        }
      }
    ]
  }
}
```