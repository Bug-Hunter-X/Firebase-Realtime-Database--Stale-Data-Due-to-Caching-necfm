# Firebase Realtime Database Stale Data Bug

This repository demonstrates a bug related to stale data resulting from client-side caching in Firebase's Realtime Database.  The bug is particularly noticeable when dealing with rapidly changing data.  The `staleDataBug.js` file showcases the problematic behavior, while `staleDataSolution.js` provides a solution using appropriate data management strategies.

## Setup

1.  Ensure you have a Firebase project set up.
2.  Install the Firebase JavaScript SDK: `npm install firebase`
3.  Replace placeholders like `<your-firebase-config>` with your actual Firebase configuration values.

## Running the Code

Execute the JavaScript files to observe the issue and the fix.  The console logs illustrate the difference between using cached data and using server-side updates.