# ATTENDANCE_SYSTEM based on IOT

Me and my team pursuing the course of Electronics and Instrumentation Engineering developed an online attendance monitoring system based on IOT under the guidance of Mrs Sreevidya P Menon and our Alumini Mr Arun.

## COMPONENTS REQUIRED

- RFID recceiver
- ESP8266 wifi module
- Google Firebase Account
- Web page ( to display the content )

## WORKING

Identity tag of students is placed on the RFID receiver and a RFID code is read by the RFID module and the code is processed. If the code is valid the ESP8266 sents corresponding data to the Google firebase Database and updates are recorded. The web page access the data from the FIREBASE database and accordingly output is displayed. Attendance will bw taken every seven Hours.A tag can only be used 7 times a day.

## INSTALLATION AND SETUP

- Google Firebase and ESP8266
- Arduino IDE
- ESP8266 setup
- Google FIREBASE account creation
- Connecting Firebase and ESP8266
- CODE for connecting to Firebase database
- Google Firebase and WEBPAGE
- Create 2 webpages : LOGIN PAGE and TABLE Page
- Create your webpage using HTML with details of representing the working Hours of your college.
- Make your web dynamic by adding JAVASCRIPT

## HOSTING YOUR WEBPAGE TO GOOGLE FIREBASE

- Step 1 : Install node.js on your system.
- Step 2 : Create a new folder on the desktop
- Step 3 : create a "public" folder inside it
- Step 4 : Paste your html login page as "index.html" inside the public folder
- Step 5 : open command prompt and go to the "new folder" created in the desktop
Type:
- $ npm install -g firebase-tools
- $ firebase init
- select your existing project
- follow the link for more details Link Here


NOTE :: CREATE A PROJECT FOR LOGIN PAGE AND HOST IT.
- :: CREATE ANOTHER PROJECT FOR TABLE AND HOST IT.
- ::COPY the URL and paste it on the Main_code in the WEBPAGE_CREATION.
- ACCESSING DATA FROM FIREBASE
- follow the this link and refer the Main_code.

## REGARDS
- To Mrs Sreevidya P Menon
- Mr.Arun alumini FISAT EIE

## TEAM MEMBERS

- John Paul
- Godson Thomas
- Derin T Jose
- Amrutha M
