**Chat App**

**Description**
This is a native mobile app built using React Native that allows users to enter a chat room, then send messages, images, and their location. Users can authenticate anonymously using Google Firebase authentication. 

**Purpose of this App**
Chat App was developed to provide an opportunity to learn about native app development, and hone the relevant skills.

**Dependencies**
1. React Native
2. Expo
3. Google Firebase
4. Google Firestore Database
5. GiftedChat
6. React Native Async Storage
7. NetInfo
8. react-native-action-sheet
9. expo-image-picker
10. expo-camera
11. expo-location
12. react-native-maps

**How to Run the Project**

1. Install Expo CLI as a global npm package: npm install --global expo-cli
2. To run the app on your smartphone download the expo app - To run the app on your computer download android studio and/or Xcode.
3. Clone repository: https://github.com/adamgutt/
4. Install all dependecies: npm install
5. Start project: expo start
6. Launch the app on your simulator.

**Setting up and Connecting to a Firebase Database**

1. Login to Google Firebase with your google account.
2. Create a new project in the firebase console.
3. On the menu select "Develop" then select "Cloud Firestore" and then select "Create Database".
4. Follow the on screen instructons to create a database (you can choose test mode for now).
5. Create a new collection called "messages".
6. Go to "Project settings", you’ll find a section called "Your apps". Click the Firestore for Web button (it may be shown as the </> icon).
7. Enter a name for your chat application and then click Register to generate the configuration code. Copy the contents of the firebaseConfig object and paste this configuration info into the firebaseConfig in Chat.js.
