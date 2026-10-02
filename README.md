# Relationship Compatibility Dashboard

Interactive relationship compatibility dashboard based on the original HTML master data.

## Features

- Firebase-ready email/password login and account creation
- Log out button
- Cloud dashboard saving to Cloud Firestore, scoped to the signed-in user
- Original browser/local JSON backup behavior preserved
- Profile View for one selected person
- Single-profile compatibility radar
- Single-profile scenario response graph
- Searchable profile cards
- Compare 2 or 3 people in one interactive radar chart
- Hover tooltips for chart points
- New profiles automatically get columns in Spider Chart Data and Scenario Study
- Existing score matrix, scenario study, future/finance, dashboard setup, reports, and original data structure preserved
- Static GitHub Pages hosting

## Firebase setup

1. Create a Firebase project and register a Web App.
2. Enable Authentication → Sign-in method → Email/Password.
3. Create a Cloud Firestore database.
4. Publish the contents of `firestore.rules` as the Firestore Security Rules.
5. Copy the Firebase Web App configuration object from the Firebase console.
6. Replace the placeholder values in `window.FIREBASE_CONFIG` in `index.html`.
7. In Firebase Authentication settings, add your GitHub Pages domain to Authorized domains if Firebase asks for it.

The Firebase browser SDK is loaded as an ES module from Google's CDN. The current HTML uses the browser-module setup documented by Firebase.