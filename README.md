# Task-management

This is the baisc javascript project for task management 
we can create new task , delete task, Update a task and also can add a description of task and much more functionalities

And the i have hosted this project on Netlify: https://compassionate-banach-abc3ff.netlify.app/

How to run it on your PC
Fork and clone it on your desktop.
run command: npm install
Before running this command make sure you have node installed in your PC. This will download all the node modules required

firebase setup
1. Log in to https://console.firebase.google.com and create new project.
2. Create a web app by clicking on icon labeled: </> , make sure you checked on the hosting while creating web app.
3. Click on Cloud firestore and create data base in test mode and location on your choice(keep it as it is if not necessary)
4. Create a collection name users and add a new document with todo(type: String), timestamp(type: timestamp) fields { this step is optional }
5. Click on setting icon present on right-side of Project Overview, then click on project setting and copy data present in general->Your apps->Firebase SDK snippet->Config->const firebaseConfig = {
6. Now go to project on your pc and go to the file src->firebase.js and paste the data copied in last step inside: const firebaseApp = firebase.initializeApp({
run command: npm start

This will start your app at http://localhost:3000/

Now you are ready to use and modify it

Star this repository if you like this project
If you have any doubts and suggesstion regarding this project feel free to contact me at http://linkedin.com/in/sonal-kenche-1657501b5
