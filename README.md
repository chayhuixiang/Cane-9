## Cane-9
<br>
This Cane-9 project was built as part of the IEEE Intuition 2023 in Nanyang Technological University.

### About
<br>
The Cane-9 project is a project that incorporates softare location tracking capabilities into the everyday walking stick used by dementia patients.
This serves to provide caregivers a means to track the location of dementia patients, to identify if they are likely to be lost, and to provide them 
with a means to get help through an alert system.

### Components
<br>
- Flutter Mobile App
- React WebApp
- Express Backend Server
- Arduino with GPS functionalities

### Key Functionalities:
<br>
- When in use, the arduino will send the location of the patient are regular intervals to the backend server. 
- The database will contain information about the list of SafeZones and their acceptable radius. 
- The location of the patient is queried from the database and reflected on the flutter mobile app. 
- Once the patient leaves the SafeZones, the mobile app will be show a button that allows the caregiver to enable the alert.
- On enable, the alert function will sound off the alarm on the cane. 
- An additional function to disable the alert will also be available for the 
caregiver.

### Tech Stack
<br>
- Flutter Mobile App
1. Flutter

- React WebaApp
1. ReactJS
2. tailwind css

- Backend Server
1. Express
2. Supabase
3. PostgreSQL
4. Docker

- Arduino
1. ESP32

### Credits
Chay Hui Xiang
Ang Kai Jun
Darren Suen Wei Jie
Ivan Loke Zhi Hao
