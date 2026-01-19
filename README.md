# CharacterEcho App Links

This repository hosts Universal Links (iOS) and App Links (Android) configuration for the CharacterEcho mobile app.

## URLs

- Share links: `https://app.characterecho.com/p/{publication_id}`
- Verification files:
  - iOS: `/.well-known/apple-app-site-association`
  - Android: `/.well-known/assetlinks.json`

## DNS Configuration

Add a CNAME record pointing `app` to `characterecho.github.io`
