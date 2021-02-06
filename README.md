# Thriftshop App Firebase Security Rules

This is the **unit tests** for security rules
of Thriftshop App using the Firebase Emulator Suite.

## Setup

To install the dependencies for this sample run `yarn` inside this directory.
You will also need the [Firebase CLI](https://firebase.google.com/docs/cli).

## Run

To run the Realtime Database tests:

To run the Cloud Firestore tests:

```
firebase emulators:exec --only firestore "yarn test-firestore"
```
