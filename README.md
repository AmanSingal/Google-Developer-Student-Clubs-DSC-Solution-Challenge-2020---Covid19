# COVID19-app

Aim of the project - To stop the spread of fake news related to Covid19 be it related to Healthcare, Travel, Precautions, Govt. Guidelines, Prevention etc.

Solution:-

Technologies used:-
1) Kodular :- For Android App Development
2) Firebase :-  Database - To store User Information, dataset for training our ML model,
                Authentication - To authenticated valid users,
                ML kit features - For performing operations related to ML model.
3) Google App Script :- For retrieving and storing information from Google Excel Sheet to Firebase and triggering ML scripts.

Usage of the app:-

-> The app is built right now only for Android Platforms. While building we took care of including the latest versions of Android.The app is expected to work well in Android version 5 onwards..
-> An internet connection is required for working with the app.
-> Download the ".apk" file named as "most_stable_version5". You are now good to go..
-> Sign Up on the app( Sign Up features helps us to authenticate the users) with your mobile number(along with country code) and    password. Right now the user can enter password in any format and its validation is not done as it not an urgent feature for right now..Future version of the app will have that.
-> Sign in to the app with the same mobile number and password.
-> Once the app opens you will be directed to Dashboard, where there is an option to copy-paste your piece of information that you want to check to be true or false. The feature is right now not activated as we are still refining our ML algorithm approach and building our dataset( as no prior dataset is available for our purpose).
-> The side bar has various options:-
    || Live tracking of cases i.e., stats of cases in respective states and in whole country with the last updated information.( We have developed this application particularly for India, therefore our stats include only Indian states..Data used for this is obtained from:- https://www.covid19india.org/)
    || Awareness page that includes latest Corona related awareness information  ranging from Social to Govt. Guidelines to Precautions to Miscallenous Information.
    || User Profile section where User's signed up mobile number is displayed along with username. The username can be changed by the user.
    || About section of the app
    || Feedback and Share pages will be created when the app will reach its final state of completion.