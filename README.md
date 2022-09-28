# INGdemo

A crossplatform app demostrating BLE services.

<img src="./img/scan.png" alt="Scan for Devices" width="100"> <img src="./img/services.png" alt="Discover Services" width="100">

<img src="./img/temp.png" alt="Temperature Service" width="100"> <img src="./img/console.png" alt="Console Service" width="100">

## Build

Use Visual Studio 2017/2019/2022 to open the solution and build it.

Note: `secrets.json` under the shared project is used to contain secrets, Web API keys, etc.
Currently this app uses Tecent/Google API for speech recognization. To build this app, 
install Mobile.BuildTools and create one like this (keys are optional for building):

```javascript
{
  "Google_app_key": "..."
}
```
