Power Status and overload (IEEE 802.3af)
----------------------------------------

| **RT-PoE commands:**                  | **PSE check after commands issued**                               |
|---------------------------------------|-------------------------------------------------------------------|
| reset                                 |                                                                   |
| detect ok                             |                                                                   |
| class 3                               |                                                                   |
| set 20                                |                                                                   |
| connect on                            |                                                                   |
|                                       | Enable power to port                                              |
|                                       | Verify that PSE sees the device taking power.                     |
| status                                | Verify that power is on.                                          |
| getv                                  | Verify that voltages are as expected.                             |
| set 350                               | Verify that PSE is providing full power.                          |
| set 390                               | Verify that PSE sees overload and shuts off power.                |
| status                                | Verify that power is off.                                         |
