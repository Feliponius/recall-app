# ReCall: public install channel

This repository only hosts the **public install page** and **signed APK releases** for the ReCall Android app
(missed-call → callback tracker for small businesses). It contains no business data, endpoints or keys.

- Install page: https://feliponius.github.io/recall-app/
- Update manifest (read by the app): https://feliponius.github.io/recall-app/manifest.json
- APKs: see Releases. Every APK is signed with the same key; the app refuses updates whose SHA-256 or signing
  certificate don't match the manifest.

Setting up a phone needs the business's private setup QR code from your ReCall provider.
