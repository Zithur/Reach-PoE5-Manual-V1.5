Class Detect, single signature mode
-----------------------------------

| **RT-PoE commands:**                          | **PSE check after commands issued**                                                       |
|-----------------------------------------------|-------------------------------------------------------------------------------------------|
| reset                                         | Verify that the PSE sees a class 0 PD.                                                    |
| detect ok                                     |                                                                                           |
| single on                                     |                                                                                           |
| mps 1                                         |                                                                                           |
| class 0                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 1 PD.                                                    |
| class 1                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 2 PD.                                                    |
| class 2                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 3 PD.                                                    |
| class 3                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 4 PD.                                                    |
| class 4                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 5 PD.                                                    |
| class 5                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 6 PD.                                                    |
| class 6                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 7 PD.                                                    |
| class 7                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE sees a class 8 PD.                                                    |
| class 8                                       |                                                                                           |
| connect on                                    |                                                                                           |
| connect off                                   | Verify that the PSE is able to detect autoclass capability, and support a load of yyy mA. |
| class aon                                     |                                                                                           |
| set yyy                                       |                                                                                           |
| connect on                                    |                                                                                           |
