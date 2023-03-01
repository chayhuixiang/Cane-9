## Cane-9
<br>
This Cane-9 project was built as part of the IEEE Intuition 2023 in Nanyang Technological University.

### About
The Cane-9 project is a project that incorporates softare location tracking capabilities into the everyday walking stick used by dementia patients. This serves to provide caregivers a means to obtain information about the real-time location of dementia patients, to identify if they are likely to be lost, and to provide them with a means to get help through an alert system. It is can also be used as  a tool for caregivers to locate the dementia patients when they are lost quickly. This involves extensive integration between the various front-end, back-end and hardware components.

### Components
- Flutter Mobile App
- React WebApp
- Express Backend Server
- Arduino with GPS functionalities

### Key Functionalities:
- When in use, the arduino will send the location of the patient are regular intervals to the backend server. 
- The database will contain information about the list of SafeZones and their acceptable radius. 
- The location of the patient is queried from the database and reflected on the flutter mobile app. 
- Once the patient leaves the SafeZones, the mobile app will be shown a button that allows the caregiver to enable the alert.
- On enable, the alert function will sound off the alarm on the cane to gain attention to the lost patient.
- An additional function to disable the alert will also be available for the caregiver.
- A QR Code is available on the cane to provide the helpers with the caregiver's contact information to ensure more efficient help

### Tech Stack

#### Flutter Mobile App
1. Flutter

#### React WebApp
1. ReactJS
2. TailwindCSS

#### Backend Server
1. Express
2. Supabase
3. PostgreSQL
4. Docker

#### Arduino
1. ESP32
2. Arduino
3. Geolocation

### Credits
- Chay Hui Xiang
- Ang Kai Jun
- Darren Suen Wei Jie
- Ivan Loke Zhi Hao
