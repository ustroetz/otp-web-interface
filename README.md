# OTP Web Interface

This is a fork of the [OTP repository](https://github.com/opentripplanner/OpenTripPlanner) and works as a standalone web interface to use the OTP API.


##### Start Web Interface
```
python -m SimpleHTTPServer
```

#### Set router and host name

edit `js/otp/config.js`

```
hostname : "http://localhost:8080",
restService: "otp/routers/manila",
```
