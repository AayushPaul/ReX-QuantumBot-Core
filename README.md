# ReX-QuantumBot-Core
This is the back-end component of ReX, an AI coach who serves as a steadfast career companion for learners, developed during my Radical AI internship. Individuals and teams face the challenge of staying in sync and maintaining productivity. QuantumBot addresses this problem by providing a platform for continuous dialogue, critical for the success of collaborative endeavors. Node.js, Firebase Firestore, and Postman API were used to develop and store unique features, such as chat history. 

## Project Setup and Usage Instructions(Documentation)  
1. Before beginning the project, ensure that you have [node.js](https://nodejs.org/en) and [Firebase CLI](https://firebaseopensource.com/projects/firebase/firebase-tools/) installed.
2. Clone your GitHub repository to your local machine using an IDE or code editor like VS Code.
3. Navigate to your project and install required dependencies using "npm install."
4. Login to firebase using "firebase login" and initialize firebase in your project using "firebase init." During the initialization, you'll be prompted to select features and services for your project. Choose the relevant options (e.g., Firestore, Functions, JSON, etc.) and follow the instructions to complete the setup.
5. Modify firebase configuration files and package.json file if needed.
6. Deploy your project to Firebase using the following command: firebase deploy. If you are using functions, then add "--only functions" to the end of the command. 
7. If you want to use emulators, run the following command: firebase emulators:start. If you are using functions, then add "--only functions" to the end of the command.

## Project Slides and Demo
[QuantumBot Slides](https://pitch.com/v/quantumbot-beqi5b)
[Loom Demo](https://www.loom.com/share/30f3cbb479af46a7b87a1067df054e31?sid=3854b0ca-8679-4b3a-9d15-f9e77432e6c9)
