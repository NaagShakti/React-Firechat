# React-FireChatRoomz

<img src="https://i.ibb.co/B6WNwW2/01.png" alt="Login" width=500>

#

<img src="https://i.ibb.co/mSHNypb/02.png" alt="Dashboard" width=500>

## Dependencies
##### 1. Node Package Manage OR Yarn
##### 2. Firebase
##### 3. Material-UI

## Setup
1. `git clone https://github.com/NaagShakti/React-Firechat.git`
2. `cd *-master`
3. Setup Firebase
    - Login To firebase.google.com.
    - Create App (web app) with Hosting Enabled.
    - Enable Gmail Authentication from Authentication Section.
    - Create Database (NOT REALTIME DATABASE) From Firestore.
    - Create Collection with your app-name.
    - Go To Config Section in Database.
    - Copy Firebase Config Data.
4. `npm install` (Installs Dependecies)
5. `npm start` OR `yarn start` (Starts Server @ localhost:3000)
#
## Deploying on Firebase.
###### 1. `firebase login`
###### 2. `firebase init`
###### 3. Select 'Hosting'.
###### 4. Select 'Use Existing Project'.
###### 5. Select App name of Your app created on Firebase.
###### 6. Input 'build' (This is Critical step. If You Input Wrong Info, Go To Step 3.).
###### 7. Input y (as in YES for Single Page Webapp).
###### 8. `npm build`
###### 9. `firebase deploy`
#
#### Notes
###### 1. This Are Practice Projects. Not Sure It Will Work. I May Have Missed Few Steps in **Setup**
###### 2. Sidebar Buttons (Except Add Channel and Channel Buttons) and Search Bar Are Non-Functional and Require Backend Programming.
###### 3. Please Share After Adding Functionality To The Other Non-Functional Components. Push-Request me Or Contact me: astitvasinha111@gmail.com
