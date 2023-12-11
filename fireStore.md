
# Getting Started with Firebase Emulator Suite

## Firebase CLI Install

Follow this guide untill to install and login to firebase
[Firebase Install Guide](https://firebase.google.com/docs/cli?authuser=0#setup_update_cli)

## Setting Up Enviorment Variables

 1. Add these vairable names to your .env file
    ```
     FIREBASE_API_KEY=
     FIREBASE_AUTH_DOMAIN=
     FIREBASE_PROJECT_ID=
     FIREBASE_STORAGE_BUCKET=
     FIREBASE_MESSAGING_SENDER_ID=
     FIREBASE_APP_ID=
     FIREBASE_MEASUREMENTID=
    ```
 2. Go to the firebase [console](https://console.firebase.google.com/u/0/) for our project
 3. Go to project settings
 4. Scroll down to Your apps
 5. Copy vairable values from the firebasConfig object into the .env file



### Start Enviorment Locally

Run the following command to start the emulation suit.

` firebase emulators:start `
