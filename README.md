# pH-Scale

A simple web application that visually represents the pH scale from 1 (Very Acidic) to 14 (Very Alkaline), with color-coded backgrounds for each pH value.

## Demo

View the live site: 
- [https://rohanraaj2.github.io/pH-Scale/](https://rohanraaj2.github.io/pH-Scale/)

## Features

- Displays the pH scale from 1 to 14.
- Color-coded backgrounds for each pH value, visually indicating acidity, neutrality, and alkalinity.
- Minimal, clean design.

## Project Structure

```
pH-Scale/
├── public/
│   ├── index.html      # Main HTML file for the app
│   └── style.css       # Styles for the pH scale
├── firebase.json       # Firebase Hosting configuration
├── .firebaserc         # Firebase project alias
├── .gitignore
└── README.md
```

## Deployment

This project is configured for [Firebase Hosting](https://firebase.google.com/docs/hosting). The `firebase.json` file sets up single-page app routing and serves files from the `public/` directory.

To deploy:
1. Install Firebase CLI:  
   `npm install -g firebase-tools`
2. Login to Firebase:  
   `firebase login`
3. Deploy:  
   `firebase deploy`
