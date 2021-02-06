# Thriftshop App Firebase Security Rules

This is the **unit tests** for security rules
of Thriftshop App using the Firebase Emulator Suite.

## Requirement
- vscode
- vscode extensions (linting and auto-format)
- node 
- npm
- yarn
- firebase-cli

## Setup

To install the dependencies for this sample run `yarn` inside this directory.
You will also need the [Firebase CLI](https://firebase.google.com/docs/cli).

## Run

To run the Realtime Database tests:

To run the Cloud Firestore tests:

```
firebase emulators:exec --only firestore "yarn test-firestore"
```

Note: `firestore.rules` is using hot reload if you need 


## [Issues](https://github.com/thriftshop-site/thriftshop/issues)

## [License](https://github.com/thriftshop-site/thriftshop/blob/main/LICENSE)

## References
- [Firebase Emulator: Install and Config](https://firebase.google.com/docs/emulator-suite/install_and_configure#startup)
- [Firebase Emulator](https://codelabs.developers.google.com/firebase-emulator#0)
- [Firebase Emulator Test](https://developers.google.com/codelabs/firebase-emulator-test-rules#0)
- [Local development with Firebase Emulator Suite](https://www.youtube.com/watch?v=yAFQVjxNWE8)

