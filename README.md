# ionic-firebase-logging

npm install

# update firebase confugratin in src\environments\environment.prod.ts and \src\environments\environment.ts

export const environment = {
  production: true,
  firebaseConfig: {
    apiKey: "",
    authDomain: "",
    databaseURL: "",
    projectId: "",
    storageBucket: "",
    messagingSenderId: "",
    appId: "",
    measurementId: ""
  }
};

npm start
