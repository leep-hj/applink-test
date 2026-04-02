# Deep Link Tester

A simple web page for testing **Custom URI Scheme** deep links on mobile devices.

Enter a scheme, host, and path to build a URI and launch your app directly from the browser.

## Supports

- **Android** — Deep Link via Intent Filter (`scheme://host/path`)
- **iOS** — Custom URL Scheme (`scheme://host/path`)

## Usage

1. Open the page on your mobile device
2. Enter your app's scheme, host, and path
3. Tap **앱 실행** to attempt to open the app

## Note

Universal Links (iOS) and App Links (Android), which use `https://` URLs,
are not supported. This tool is intended for custom scheme testing only.
