
<html>
<head>
</head>
<body>
<p>hello</p>
Receive email updates about new Firebase features, research, and events
jovipage
Waiting for Analytics data...
Store and sync app data in milliseconds

Authentication
Authenticate and manage users

Cloud Firestore
Realtime updates, powerful queries, and automatic scaling
See all Build features
Keep tabs on your app’s quality

Crashlytics
Prioritize and fix stability issues

Performance
Get insights into your app's performance
See all Release & Monitor features
Grow & engage your audience

Cloud Messaging
Engage the right users at the right time

A/B Testing
Improve key flows & notifications
See all Engage features
Deploy extended functionality to your app quickly

Extensions
Pre-packaged solutions that save you time
See all Extensions features
See all Firebase features
Add a web app
Completed
2
Add Firebase SDK
Use npm 
Use a <script> tag 
Copy and paste these scripts into the bottom of your <body> tag, but before you use any Firebase services:

<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/9.6.8/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.6.8/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyCdJ2cIiGu00ft3YOxTZW11HbIRsN-iqwc",
    authDomain: "jovipage-31009.firebaseapp.com",
    projectId: "jovipage-31009",
    storageBucket: "jovipage-31009.appspot.com",
    messagingSenderId: "296208187657",
    appId: "1:296208187657:web:37d782bfb1ca802ca913d8",
    measurementId: "G-EEH7ZNPSQC"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
</body>
</html>
