// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyCV0wBawGHOy6Ndf4Kik6X6IL_i9uezNOI",
  authDomain: "my-project-panel-79e1c.firebaseapp.com",
  projectId: "my-project-panel-79e1c",
  storageBucket: "my-project-panel-79e1c.firebasestorage.app",
  messagingSenderId: "1003291498298",
  appId: "1:1003291498298:web:0a5645a8173a140c626203",
  measurementId: "G-D8EX27WQN9"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
