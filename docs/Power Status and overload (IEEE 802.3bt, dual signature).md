Power Status and overload (IEEE 802.3bt, dual signature) 
---------------------------------------------------------

| **RT-PoE commands:**                            | **PSE check after commands issued**                                  |
|-------------------------------------------------|----------------------------------------------------------------------|
| reset                                           |                                                                      |
| detect ok                                       |                                                                      |
| single off                                      |                                                                      |
| class 5                                         |                                                                      |
| set 20                                          |                                                                      |
| connect on                                      |                                                                      |
|                                                 | Enable power to port                                                 |
|                                                 | Verify that PSE sees the device is taking power.                     |
| status                                          | Verify that power is on.                                             |
| getv                                            | Verify that voltages are as expected.                                |
| set 1426                                        | Verify that PSE is providing full power.                             |
| set 2000                                        | Verify that PSE sees overload and shuts off power.                   |
| status                                          | Verify that power is off.                                            |
