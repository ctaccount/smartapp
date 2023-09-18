{
    "resourceType": "QuestionnaireResponse",
    "id": "response1",
    "contained": [
        {
            "resourceType": "Questionnaire",
            "id": "adaptive-questionnaire",
            "extension": [
                {
                    "url": "http://hl7.org/fhir/uv/sdc/StructureDefinition/sdc-questionnaire-questionnaireAdaptive",
                    "valueBoolean": true
                }
            ],
            "status": "active",
            "item": [
                {
                    "linkId": "b9762ada-46f5-4f8f-b066-ae0fc7e32671",
                    "type": "group",
                    "item": [
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "CPTCode",
                            "prefix": "1.",
                            "text": "CPT Code",
                            "type": "string"
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "ReviewType",
                            "prefix": "2.",
                            "text": "Review Type",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "FHIRMedicalNecessity"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "RCTYPE",
                            "prefix": "3.",
                            "text": "RCTYPE",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "RCPROS"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "episodeId",
                            "prefix": "4.",
                            "text": "Case ID",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "DEFAULT"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "userId",
                            "prefix": "5.",
                            "text": "Patient Name",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "DEFAULT"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "Age",
                            "prefix": "6.",
                            "text": "Age",
                            "type": "decimal",
                            "initial": [
                                {
                                    "valueDecimal": 58
                                }
                            ]
                        },
                        {
                            "linkId": "Gender",
                            "prefix": "7.",
                            "text": "Gender",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "female"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "InsCarrier",
                            "prefix": "8.",
                            "text": "Insurance Carrier Key",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "OXFORD"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "AuthorizationStatus",
                            "prefix": "9.",
                            "text": "Authorization Status",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "IN REVIEW"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "RoleType",
                            "prefix": "10.",
                            "text": "Role Type",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "MD"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "InsPlanCode",
                            "prefix": "11.",
                            "text": "Ins Plan Code",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "Medicare"
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "text-box"
                                            }
                                        ]
                                    }
                                }
                            ],
                            "linkId": "LOB",
                            "prefix": "12.",
                            "text": "LOB",
                            "type": "string",
                            "initial": [
                                {
                                    "valueString": "Medicare"
                                }
                            ]
                        }
                    ]
                },
                {
                    "linkId": "3e9e9bd5-b4b7-41c2-ab48-a5302ba03aea",
                    "type": "group",
                    "item": [
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-itemControl",
                                    "valueCodeableConcept": {
                                        "coding": [
                                            {
                                                "system": "http://hl7.org/fhir/questionnaire-item-control",
                                                "code": "dropdown"
                                            }
                                        ]
                                    }
                                },
                                {
                                    "url": "ReferenceTag",
                                    "valueString": "DISTANT_METS"
                                }
                            ],
                            "linkId": "12122841",
                            "prefix": "1.",
                            "text": "Does the patient have a history of distant metastases (stage M1) (i.e. to brain, lung, liver, bone)?",
                            "type": "choice",
                            "answerOption": [
                                {
                                    "valueCoding": {
                                        "code": "25145670",
                                        "display": "Yes"
                                    }
                                },
                                {
                                    "valueCoding": {
                                        "code": "25145671",
                                        "display": "No"
                                    }
                                }
                            ]
                        },
                        {
                            "extension": [
                                {
                                    "url": "http://hl7.org/fhir/StructureDefinition/questionnaire-hidden",
                                    "valueBoolean": true
                                }
                            ],
                            "linkId": "ReviewId",
                            "prefix": "2.",
                            "text": "5280198",
                            "type": "display"
                        },
                        {
                            "linkId": "CreatedEpisodeId",
                            "prefix": "3.",
                            "text": "Episode Id: D500035367",
                            "type": "display"
                        }
                    ]
                }
            ]
        }
    ],
    "questionnaire": "#adaptive-questionnaire",
    "status": "in-progress",
    "subject": {
        "reference": "Patient/37922454-e52f-11ed-8e0e-0a81ea1b064c"
    },
    "authored": "2023-08-15",
    "item": [
        {
            "linkId": "b9762ada-46f5-4f8f-b066-ae0fc7e32671",
            "item": [
                {
                    "linkId": "CPTCode",
                    "text": "CPT Code",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "manual"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "RCPROS"
                        }
                    ]
                },
                {
                    "linkId": "ReviewType",
                    "text": "Review Type",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "FHIRMedicalNecessity"
                        }
                    ]
                },
                {
                    "linkId": "RCTYPE",
                    "text": "RCTYPE",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "RCPROS"
                        }
                    ]
                },
                {
                    "linkId": "episodeId",
                    "text": "Case ID",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "DEFAULT"
                        }
                    ]
                },
                {
                    "linkId": "userId",
                    "text": "Patient Name",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "DEFAULT"
                        }
                    ]
                },
                {
                    "linkId": "Age",
                    "text": "Age",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueDecimal": 58
                        }
                    ]
                },
                {
                    "linkId": "Gender",
                    "text": "Gender",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "female"
                        }
                    ]
                },
                {
                    "linkId": "InsCarrier",
                    "text": "Insurance Carrier Key",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "OXFORD"
                        }
                    ]
                },
                {
                    "linkId": "AuthorizationStatus",
                    "text": "Authorization Status",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "IN REVIEW"
                        }
                    ]
                },
                {
                    "linkId": "RoleType",
                    "text": "Role Type",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "MD"
                        }
                    ]
                },
                {
                    "linkId": "InsPlanCode",
                    "text": "Ins Plan Code",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "Medicare"
                        }
                    ]
                },
                {
                    "linkId": "LOB",
                    "text": "LOB",
                    "answer": [
                        {
                            "extension": [
                                {
                                    "extension": [
                                        {
                                            "url": "source",
                                            "valueCode": "auto"
                                        }
                                    ],
                                    "url": "http://hl7.org/fhir/us/davinci-dtr/StructureDefinition/information-origin"
                                }
                            ],
                            "valueString": "Medicare"
                        }
                    ]
                }
            ]
        }
    ]
}
