Class Detect, dual signature mode
---------------------------------

| **RT-PoE commands:**                      | **PSE check after commands issued**                                                       |
|-------------------------------------------|-------------------------------------------------------------------------------------------|
| reset                                     | Verify that the PSE sees a legacy class 0 PD.                                             |
| detect ok                                 |                                                                                           |
| single off                                |                                                                                           |
| class 0                                   |                                                                                           |
| connect on                                |                                                                                           |
| connect off                               | Verify that the PSE sees a compliant class 1 PD.                                          |
| class 1                                   |                                                                                           |
| connect on                                |                                                                                           |
| connect off                               | Verify that the PSE sees a legacy class 1 PD.                                             |
| class 1L                                  |                                                                                           |
| connect on                                |                                                                                           |
| connect off                               | Verify that the PSE sees a compliant class 5 PD.                                          |
| class 5                                   |                                                                                           |
| connect on                                |                                                                                           |
| connect off                               | Verify that the PSE is able to detect autoclass capability, and support a load of xxx mA. |
| class aon                                 |                                                                                           |
| set xxx                                   |                                                                                           |
| connect on                                |                                                                                           |
