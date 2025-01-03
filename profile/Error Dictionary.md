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

| NAME | ERROR CODE | Desc |
| ------ | ------ | ------ |
| MAINTENANCE | 500 | Maintenenace Internal API |
| SERVER_ERROR | 503 | Internal Server Error |
| MAINTENANCE | error_N000 | (W-Matrix) Fail to get config from server. Please try again. |
| MAINTENANCE | error_N001 | (W-Matrix) No response from server. Please try again. |
| MAINTENANCE | error_N002 | (W-Matrix) App ID is different from server. |
| MAINTENANCE | error_N003 | (W-Matrix) Fail to generate WebSquare JS files. |
| MAINTENANCE | error_N004 | (W-Matrix) Server Error is occurred. |
| MAINTENANCE | error_N005 | (W-Matrix) Failed to start W-Matrix. |
| MAINTENANCE | error_N006 | (W-Matrix) Server list configuration failed. |
| MAINTENANCE | error_F001 | (W-Matrix) Fail to unzip Engine zip file. |
| MAINTENANCE | error_F002 | (W-Matrix) Fail to unzip Resource zip file. |
| MAINTENANCE | error_F003 | (W-Matrix) Fail to unzip Custom Update zip file. |
| MAINTENANCE | error_F004 | (W-Matrix) Fail to unzip Refresh Update zip file. |
| MAINTENANCE | error_F005 | (W-Matrix) Refresh Update Hash Table is not valid. |
| MAINTENANCE | error_F006 | (W-Matrix) Fail to download Refresh Update File. |
| MAINTENANCE | error_F007 | (W-Matrix) WebSquare License is not valid. |
| MAINTENANCE | error_F009 | (W-Matrix) The app cannot be run with the current version of %s. Please update to the latest version on the Play Store and restart. |
| MAINTENANCE | error_W1004 | (W-Matrix) W-Matrix License is not valid. |
| MAINTENANCE | error_W1005 | (W-Matrix) Fail to create WebView. |
| MAINTENANCE | error_O1000 | (W-Matrix) An error occurred while setting offline mode. |
| MAINTENANCE | error_O1001 | (W-Matrix) There is no W-Matrix setup to use offline mode. |

### Version
This code is used to identify the version status of either no update, force or soft update

| NAME | ERROR CODE |
| ------ | ------ |
| SOFT_UPDATE | VER0 |
| FORCE_UPDATE | VER1 |
| NO_UPDATE | VER-1 |
