# Bots Sample Web App Readme (v. 18.2.3.0)#
## Overview ##
The ChatSample app that's included in the `bots-client-sdk-js-samples-18.2.3.0.zip` file is a mobile app that demonstrates communication with the Oracle Bots server. To get this SDK, download `bots-client-sdk-js-18.2.3.0.zip` from the [Oracle Technology Network’s OMCE downloads page](http://www.oracle.com/technetwork/topics/cloud/downloads/mobile-suite-3636471.html).
## Usage ##
This sample app provides an end-to-end example that you can reference when building your own mobile app. It shows you how to initialize the Bots SDK using an App ID that's generated by Oracle Intelligent Bots (Bots) and how you can chat with other bots just by changing this App ID.
## Supported Browsers ##

The ChatSample app supports all popular browsers.
### Desktop Versions ###
- Chrome: The latest release along with the previous major release.
- Edge: The latest release along with the previous major release.
- Firefox: The latest version along with the previous major release.
- Internet Explorer: Version 11 and higher.
- Safari: The latest release along with the previous major release.
### Mobile Versions ###
- Stock browser on Android 4.1 and higher
- Safari on iOS 8 and higher
### Bots SDK
This sample app already has the Bots Client SDK for JavaScript included in the project. This SDK is compiled for the localhost environment only.
To use the SDK in another location, download it and  follow the readme file to compile it on your server.

### Configuration file
Required parameters for Bots SDK:
```json
{
  "mode": "botsSDK",
  "appId": "APPLICATION_ID",
  "sdkUrl": "SDK_FOLDER_URL"
}
```

## Generate the App ID ##
1. In your Oracle Intelligent Bots instance, open your bot, choose **Settings** in the left navbar, and then choose **Channels**.
1. Click **Add Channel** and then complete the dialog, choosing **Web** as the channel type. After you complete this dialog, Bots will generate the App Id that you need to initialize the Bots SDK. Keep it close at hand.
## Installation and Runtime Setup ##
1. Navigate to the `ChatSample` app directory.
1. Run `npm install`.
1. Run `node server.js`.
1. In your browser, open `http://localhost:3000`.
1. Enter the App ID that was generated by Oracle Bots in the field on the home page. (You also embedded this APP ID in the sample app.) The Bots' chat window will be initialized and loaded.
##License##
Copyright (c) 2018 Oracle Corporation and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.