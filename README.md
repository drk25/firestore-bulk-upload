# firestore-bulk-upload

bulk upload firestore collection
To run add 2 additional file, both can be download from firebase project

1. serviceAccount.json

  ```json
  {
  "type": "service_account",
  "project_id": "project id",
  "private_key_id": "key....",
  "private_key": "",
  "client_email": "",
  "client_id": "",
  "auth_uri": "",
  "token_uri": "",
  "auth_provider_x509_cert_url": "",
  "client_x509_cert_url": ""
}
  ```
  
2. config.js

  ```javascript
  
   const firebaseConfig = {
    apiKey: "",
    authDomain: "",
    databaseURL: "",
    projectId: "",
    storageBucket: "",
    messagingSenderId: "",
    appId: "",
    measurementId: ""
  };

  module.exports = firebaseConfig;
  ```
  3. start 
  ```shell
  node import.js
  ```
  
