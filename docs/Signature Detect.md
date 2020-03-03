Signature Detect
----------------

| **RT-PoE commands:**           | **PSE check after commands issued**                     |
|--------------------------------|---------------------------------------------------------|
| reset                          | Verify that the PSE recognizes a valid PD.              |
| detect ok                      |                                                         |
| mps on                         |                                                         |
| connect on                     |                                                         |
| connect off                    | Verify that the PSE detects a low signature resistance. |
| detect lo                      |                                                         |
| connect on                     |                                                         |
| connect off                    | Verify that the PSE recognizes a valid PD.              |
| detect ok                      |                                                         |
| connect on                     |                                                         |
| connect off                    | Verify that the PSE detects a bad capacitance.          |
| cap on                         |                                                         |
| connect on                     |                                                         |
