

*********** FIREBASE CONFIGURATION TO A FlUTTER APP USING FlutterFire CLI *******************

----------------------> Part 1: Firebase Configuration and Connections

1. create firebase account using google email
2. run these command in terminal:
    *dart pub global activate flutterfire_cli         -------------------> to instal CLI package
    *firebase login                                   -------------------> to login in firebase via terminal to link with your project
    firebase projects:list                            -------------------> to display all your projects
    flutterfire configure                             -------------------> to configure firebase to your local project
    
3. Step by step questions involved in flutterfire configure:
       * ? Please sign in to your Google account------------------------------------------->if you are not logged in
       * ? Select a Firebase project to configure your Flutter application-----------------> You have to create first or just create now
       * ? Which platforms should your configuration support?------------------------------>select Ios & Android
       * ? Enter your Android package name------------------------------------------------->cargo.mosimba.com
       * ? Android app already exists. Overwrite configuration?---------------------------->YES
       ? Would you like to generate firebase_options.dart?  -------------------------------> YES
       
4. After completion "GoogleService-Info.plist" and "google-services.json" will be already dowmloaded and configured themselves


---------------> Part 2: Provision of the SHA-1 as app fingerprint to a firebase 
5. run the following to get SHA-1 to app fingerprint key characters:

   ********* in ubuntu :
            cd android
            ./gradlew signingReport
  
   **********in window :
            gradlew signingReport


---------------> Part 3 :  Firebasse Initilization
6.instal the following packages by commands:
       flutter pub add firebase_core
       flutter pub add firebase_auth
   
7. In main.dart add this code after widget initialization:
         await Firebase.initializeApp(
           options: DefaultFirebaseOptions.currentPlatform,
                    );
                    
6. from that you can read documentaion or ask AI for snippets code for your desired task or feature such as:
                * google email signup & signin
                * authentication via sms otp
                * firestorage or cloud storage
       

