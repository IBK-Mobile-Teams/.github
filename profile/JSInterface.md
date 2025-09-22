# JS Interface

## Request to Android
```javascript
Android.requestNative(id, requestData, callBackName)
```

## Request to IOS
```javascript

```

## Define Native Request
```javascript
const NativeRequest = Object.freeze({
  SHOW_KEYBOARD_PIN: Object.freeze({
    requestId: "SHOW_KEYBOARD_PIN",
    callBackName: "onResultPin"
  }),
  SHOW_M_OTP: Object.freeze({
    requestId: "SHOW_M_OTP",
    callBackName: "onResultMOtp"
  }),
  GO_HOME: Object.freeze({
    requestId: "GO_HOME",
  }),
});
```

## Dictionary Native Request

<table>
  <thead>
    <tr>
      <th>Request</th>
      <th>RequestId</th>
      <th>CallBackName</th>
      <th>Data</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Show Native Keyboard Pin</td>
      <td>SHOW_KEYBOARD_PIN</td>
      <td>onResultPin</td>
      <td>null</td>
    </tr>
    <tr>
      <td>Show M-OTP Pin</td>
      <td>SHOW_M_OTP</td>
      <td>onResultMOtp</td>
      <td>null</td>
    </tr>
    <tr>
      <td>Go Home Page</td>
      <td>GO_HOME</td>
      <td>null</td>
      <td>null</td>
    </tr>
    <tr>
      <td>On Share</td>
      <td>ON_SHARE</td>
      <td>null</td>
      <td>null</td>
    </tr>
  </tbody>
</table>
