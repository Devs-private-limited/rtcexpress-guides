# RTCExpress public integration guides

This repository contains the public documentation entry point for RTCExpress,
a platform for adding room chat, voice calls, and video calls to web and mobile
applications.

It intentionally contains no server source code, App Secrets, access tokens,
production configuration, customer information, or private SDK packages.

## Start here

- [Voice, video, and chat API integration guide](https://rtc.devsquarelabs.com/guides/voice-video-chat-api)
- [WebRTC video calling API integration guide](https://rtc.devsquarelabs.com/guides/webrtc-video-calling-api)
- [JavaScript voice calling tutorial](https://rtc.devsquarelabs.com/tutorials/javascript-voice-calling)
- [JavaScript video calling tutorial](https://rtc.devsquarelabs.com/tutorials/javascript-video-calling)
- [JavaScript in-app chat tutorial](https://rtc.devsquarelabs.com/tutorials/javascript-in-app-chat)
- [RTCExpress developer hub](https://rtc.devsquarelabs.com/developers)
- [API reference](https://rtc.devsquarelabs.com/api-reference)

## Integration principles

1. Authenticate each person in your own backend.
2. Keep the App Secret only on that backend.
3. Issue a short-lived, room-scoped token to the client.
4. Join the authorized room before enabling chat or call controls.
5. Test two real devices, permissions, reconnects, and network changes before launch.

## Install the SDKs

| Platform | Install | Package |
|---|---|---|
| Web (JavaScript/TypeScript) | `npm install rtcexpress` | [npm](https://www.npmjs.com/package/rtcexpress) |
| Flutter | `flutter pub add rtcexpress` | [pub.dev](https://pub.dev/packages/rtcexpress) |
| React Native | `npm install rtcexpress-react-native` | [npm](https://www.npmjs.com/package/rtcexpress-react-native) |

Flutter and React Native support Android today; iOS is experimental. Platform
guides: [Web](https://rtc.devsquarelabs.com/sdk/web),
[Flutter](https://rtc.devsquarelabs.com/sdk/flutter),
[React Native](https://rtc.devsquarelabs.com/sdk/react-native),
[Android](https://rtc.devsquarelabs.com/sdk/android).

For implementation help, contact
[support@devsquarelabs.com](mailto:support@devsquarelabs.com).

## Security

Please do not open an issue containing secrets, tokens, customer data, or a
security vulnerability. Send security-related reports to
[support@devsquarelabs.com](mailto:support@devsquarelabs.com).

