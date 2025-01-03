# Error Dictionary
```
This page is documentation of Error Dictionary for Mobile App IBK Bank Indonesia
```
> @autor of this page [derysudrajat](https://github.com/derysudrajat-ibk) | [reva](https://github.com/revarino)

## Blocking Error

| NAME | ERROR CODE |
| ------ | ------ |
| DEFAULT | -1 |

### Time Drift
The error indicated the user device is not set as automatic time

| NAME | ERROR CODE |
| ------ | ------ |
| NON_AUTO | TD01 |

### DroidX / ixShield
The error indicated there are some problems with Library DroidX on Android or ixShield on iOS

| NAME | ERROR CODE |
| ------ | ------ |
| ERROR_ROOT | DXR-1, DXR-2, DXR1, DXR2, DXR3 |
| ERROR_MALWARE | DXM-1, DXM-2, DXM1 |
| ERROR_MALWARE_REALTIME | DXRTM-1, DXRTM-2, DXRTM1 |
| ERROR_UPDATE | DXU1, DXU2, DXU3, DXU4, DXU5, DXU6, DXU7, DXU8 |
| ERROR_INIT | DXI1, DXI2, DXI3, DXI4, DXI5, DXI6, DXI7, DXI8, DXI9, DXI10, DXI11, DXI12, DXI13, DXI14, DXI15, DXI100, DX101, DXI102 |

### Security Library
The error indicated there are errors during generating or exchanging keys from Native and BackEnd

| NAME | ERROR CODE |
| ------ | ------ |
| FAILED_GET_DEVICE_ID | SC01 |
| UN_AUTHORIZED | 401 |

### Server
The error is that there is a problem with the server or there are maintenance schedules

| NAME | ERROR CODE |
| ------ | ------ |
| MAINTENANCE | 500 |
| SERVER_ERROR | 503 |

### Version
This code is used to identify the version status of either no update, force or soft update

| NAME | ERROR CODE |
| ------ | ------ |
| SOFT_UPDATE | VER0 |
| FORCE_UPDATE | VER1 |
| NO_UPDATE | VER-1 |
