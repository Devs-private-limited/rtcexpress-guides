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
- [Flutter voice calling tutorial](https://rtc.devsquarelabs.com/tutorials/flutter-voice-calling)
- [Android (Kotlin) voice calling tutorial](https://rtc.devsquarelabs.com/tutorials/android-voice-calling)
- [React Native voice calling tutorial](https://rtc.devsquarelabs.com/tutorials/react-native-voice-calling)
- [Free TURN server guide](https://rtc.devsquarelabs.com/guides/free-turn-server)
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
| Android (Kotlin) | `implementation("com.devsquarelabs:rtcexpress-android")` | [Maven Central](https://central.sonatype.com/artifact/com.devsquarelabs/rtcexpress-android) |
| Node.js server (tokens) | `npm install rtcexpress-server` | [npm](https://www.npmjs.com/package/rtcexpress-server) |

Flutter and React Native support Android today; iOS is experimental. Platform
guides: [Web](https://rtc.devsquarelabs.com/sdk/web),
[Flutter](https://rtc.devsquarelabs.com/sdk/flutter),
[React Native](https://rtc.devsquarelabs.com/sdk/react-native),
[Android](https://rtc.devsquarelabs.com/sdk/android),
[Node.js server](https://rtc.devsquarelabs.com/sdk/node).

## Pricing

The [Free plan](https://rtc.devsquarelabs.com/pricing) includes in-app chat and
2,000 voice minutes a month for 1:1 calls. Paid plans are a flat monthly price
from $9, never billed per minute. See how RTCExpress compares with
[Agora, Twilio Video, ZEGOCLOUD and Sendbird](https://rtc.devsquarelabs.com/compare).

For implementation help, contact
[support@devsquarelabs.com](mailto:support@devsquarelabs.com).

## Security

Please do not open an issue containing secrets, tokens, customer data, or a
security vulnerability. Send security-related reports to
[support@devsquarelabs.com](mailto:support@devsquarelabs.com).

---

RTCExpress is built by [Devsquare Labs](https://devsquarelabs.com). Website:
[rtc.devsquarelabs.com](https://rtc.devsquarelabs.com).
