Hosting Next.js + React app in Firebase with Firebase Hosting and Functions.
This project is mere a copy of project https://github.com/jthegedus/firebase-functions-next-example, with few small required changes when you are developing and building that project in windows system.

Google Firebase Hosting is a Linux based system, when you develop an application on windows and try to deploy it in Firebase hosting you may encounter some errors like -

1. "Error: Cannot find module '/user_code/next/server/static\*\pages\index.js". 
OR
2. "Error: Could not find a valid build in the '/user_code/next' directory! Try building your app with 'next build' before starting the server".
OR
3. "'NODE_ENV' is not recognized as an internal or external command"


This project handles all those errors
