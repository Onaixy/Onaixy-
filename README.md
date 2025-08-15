# Core setup 
All in one ai tools website. 
# React project banaiye
npx create-react-app onaixy-core-setup

cd onaixy-core-setup

# Firebase install karein
npm install firebase

# GitHub Pages deploy package install karein
npm install gh-pages --save-dev

{
  "homepage": "https://USERNAME.github.io/onaixy-core-setup",
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}

import { initializeApp } from "firebase/app";
import { getFirestore } from "firebase/firestore";
import { getAuth } from "firebase/auth";

const firebaseConfig = {
  apiKey: "YOUR-API-KEY",
  authDomain: "YOUR-PROJECT.firebaseapp.com",
  projectId: "YOUR-PROJECT-ID",
  storageBucket: "YOUR-PROJECT.appspot.com",
  messagingSenderId: "YOUR-SENDER-ID",
  appId: "YOUR-APP-ID"
};

const app = initializeApp(firebaseConfig);
export const db = getFirestore(app);
export const auth = getAuth(app);

import React from "react";
import { auth } from "./firebase";

function App() {
  return (
    <div style={{ textAlign: "center", marginTop: "50px" }}>
      <h1>Onaixy.com Live Test</h1>
      <p>React + Firebase + GitHub Pages</p>
    </div>
  );
}

export default App;

# Git init karein
git init
git remote add origin https://github.com/USERNAME/onaixy-core-setup.git
git add .
git commit -m "Initial Commit"
git push -u origin main

# Deploy karein
npm run deploy
