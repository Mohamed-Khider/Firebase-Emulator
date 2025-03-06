Learn how to develop a web app with the Firebase Emulator Suite.

how to use this repo?

requirment :
  1-node js 18 or later
  2-java 17 or later

installation:
1- clone the repo int your local machine.
    https://github.com/Mohamed-Khider/Firebase-Emulator.git
    
2- open terminal on the root of the repo and install Firebase CLI
    $ npm install -g firebase-tools
    
3- now you have to ligin to you firebase consol and setup new project remeber your project id after setup

4- got back to project on terminal login to you firbase acccount and use the project you have setup using : 
          $ firebase login
          $ firebase use Enter-project-id
          
5- cd to functions folder and install depen...
    $ npm install

6- now go back to the root and run the emulator 
    $ firebase emulators:start --import=./seed
    Once you see the All emulators started message, the app is ready to use. now open the browser on the port showing on terminal you will see firebase emulator suit UI
  
