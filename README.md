# Real-Time Geolocation Tracking with React Native #

⚠️ This tutorial is out of date: While this tutorial series contains useful information, this post was originally written using PubNub's React SDK V1. Check out our [React SDK Docs](https://www.pubnub.com/docs/sdks/react) for an up-to-date reference. You can learn more about how PubNub powers [thousands of customers](https://www.pubnub.com/customers/) worldwide in our [PubNub for Developers](https://www.pubnub.com/developers/) resources. Have suggestions or questions about the content of this post? Reach out to devrel@pubnub.com.⚠️

In this [tutorial](https://www.pubnub.com/blog/realtime-geo-tracking-app-react-native/), you'll learn how easy it is to build real-time [geolocation tracking](https://www.pubnub.com/use-case/geolocation/) with PubNub and React Native, one of the most popular mobile app frameworks. The geolocation application renders multiple users on a map view, allowing users to toggle their location permissions as well as click a button to zoom the map on their location. You'll also be able to determine how many users are currently online in the app using [PubNub Presence](https://www.pubnub.com/docs/general/presence/overview).

## Environment Setup
In order to start the development process, you are going to need to prepare a few prerequisites.
* Visual Studio Code.
* A [PubNub Account](https://admin.pubnub.com/#/login). A PubNub account is always free, and is necessary to obtain the API keys necessary for online play. Enable [Presence](https://www.pubnub.com/how-to/admin-portal-presence/) and [Message Persistence](https://www.pubnub.com/how-to/admin-portal-persistence/). Learn more about how to create keys with this written and video [walkthrough](https://www.pubnub.com/how-to/admin-portal-create-keys/), specifically for Presence and Message Persistence. Copy the publish and subscribe keys to a text editor, as you'll need these later on.
* Node.js
* Terminal / Console
* XCode (for iOS simulation)
* Android Studio (for Android simulation)
* Install React Native CLI
```
sudo npm install -g react-native-cli
sudo npm install -g react-native
```
## Build & Run

In the constructor in App.js, replace your publish and subscribe keys with the string values respectively. 

Save any changes, and run the application with iOS devices using ```react-native run-ios``` or ```react-native run-android``` for Android devices.

## Links
- PubNub Account: https://admin.pubnub.com/#/login
- React SDK: https://www.pubnub.com/docs/sdks/react
- Tutorial Link: https://www.pubnub.com/blog/realtime-geo-tracking-app-react-native/

## License
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
