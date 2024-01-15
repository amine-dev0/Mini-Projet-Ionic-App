# Simple Note App (CRUD)
# Mini Projet ionic app

A mobile note-taking application developed with Angular, Ionic, and Firebase. This app provides basic CRUD (Create, Read, Update, Delete) functionality for managing notes.

## Features

- Create new notes with a title and content.
- Read and view existing notes.
- Update notes to modify their content.
- Delete notes to remove unwanted entries.

## Prerequisites

Ensure you have the following tools installed before running the app:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Angular CLI](https://angular.io/cli)
- [Ionic CLI](https://ionicframework.com/docs/intro/cli)
- [Firebase CLI](https://firebase.google.com/docs/cli)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/amine-dev0/Mini-Projet-Ionic-App.git


2. Navigate to the project directory:

    ```bash
    cd note-app

3. Install dependencies:
    
    ```bash
    npm install

### Firebase Configuration

1. Create a Firebase project on the Firebase Console.

2. Obtain your Firebase configuration from Project Settings > Your apps > Firebase SDK snippet > Config.

3. Replace the placeholder in src/environments/environment.ts with your Firebase config.

    ```bash
    export const environment = {
     production: false,
     firebaseConfig: {
       apiKey: 'YOUR_API_KEY',
       authDomain: 'YOUR_AUTH_DOMAIN',
       projectId: 'YOUR_PROJECT_ID',
       storageBucket: 'YOUR_STORAGE_BUCKET',
       messagingSenderId: 'YOUR_MESSAGING_SENDER_ID',
       appId: 'YOUR_APP_ID',
     },
   };

4. Update src/environments/environment.prod.ts for production.
    ```bash
    ionic serve

5. Deploying to Firebase Hosting

6. Install Firebase tools globally if not installed:

    ```bash
    npm install -g firebase-tools

7. Login to your Firebase account:

    ```bash
    firebase login

8. Initialize Firebase project:

    ```bash
    firebase init

### Follow the prompts to set up Firebase Hosting.
9. Deploy the app:

    ```bash
    firebase deploy

### Your note app is now deployed to Firebase Hosting.
