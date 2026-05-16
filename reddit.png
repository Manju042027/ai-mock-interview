import { initializeApp, getApp, getApps } from "firebase/app";
import { getAuth } from "firebase/auth";
import { getFirestore } from "firebase/firestore";

const firebaseConfig = {
  apiKey: "AIzaSyA_MtkrDwQzJVboSu-vBdIUfgdVq36oa_Q",
  authDomain: "project-k-b2db8.firebaseapp.com",
  projectId: "project-k-b2db8",
  storageBucket: "project-k-b2db8.appspot.com", 
  messagingSenderId: "735973916161",
  appId: "1:735973916161:web:4bb8350d389d8049780a00",
  measurementId: "G-PV3SDMLFTJ"
};


const app = !getApps().length ? initializeApp(firebaseConfig) : getApp();

export const auth = getAuth(app);
export const db = getFirestore(app);
