# System.Security namespace Extensions

## System.Security.OTP

### IOneTimePassword

* string GenerateCode()
* bool VerifyCode(string expectedCode)

### ITimeBasedOneTimePassword

* int ExpireSeconds
* int GetRemainingSeconds(DateTime dateTime)

### ICounterBasedTimePassword

* int Counter

#### GoogleOTP
#### SamsungServiceModeOTP