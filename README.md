# safeZone
Community driven , safety app , for crime prevention , https://www.linkedin.com/posts/alisadiyathool_safezone-communitysafety-androiddevelopment-activity-7265775555403280385-fH8x?utm_source=share&amp;utm_medium=member_desktop&amp;rcm=ACoAAD0V0-YBej7QsgJ4uYWgHHnH91d618iBENA
# SafeZone Crime Detection - README

**Application Name:** SafeZone Crime Detection  
**Version:** 3.0  

Welcome to the SafeZone Crime Detection README! This application is an Android-based platform designed to enhance public safety in South Africa by allowing users to report crime, access emergency resources, and safeguard their personal security. Created as part of the OPSC7312-POE project by Alisa Diya Thool through GitHub Classroom, SafeZone Crime Detection is packed with features to provide timely assistance and information to users in emergency situations.

---
## Google play links ( closed testing ) 
https://play.google.com/store/apps/details?id=com.alisa.safezone
https://play.google.com/apps/testing/com.alisa.safezone

---
## SafeZone demo + Google Console demo + FireBase Demo + Room DB 
https://youtu.be/GuaD1yU6478
---
## Description

SafeZone Crime Detection empowers users to document crime hotspots, report incidents, and access survival information through a user-friendly, interactive interface. Key functionalities include an SOS SMS feature, which enables users to send their location to a trusted contact in emergencies, and a dedicated API that shares safety tips and emergency contacts in South Africa. Users can also customize their experience with language preferences, biometric login, and a community event calendar , where you can save events straight to your calander 

---
## Application Features

### 1. **Splash Screen**
   - The app opens with a splash screen displaying the SafeZone logo, lasting for 5 seconds.

### 2. **About Screen**
   - Provides a brief overview of SafeZone’s purpose and functionalities. Users can start by creating an account through the "Let's Get Started" button.

### 3. **Register Screen**
   - Users create an account by entering their username, email, and password (with confirmations).
   - Google Single Sign-On (SSO) is available for streamlined registration.

### 4. **Login Screen**
   - Users log in with their credentials or biometric authentication if they have previously signed in, accessing SafeZone’s full suite of features.
   - Credentials to use to login
     email : ally1@gmail.com
     password: ally1#
     

### 5. **Crime Detection Heat Map & SOS SMS**
   - Users can add markers on a map to indicate crime hotspots, specifying the type of crime at each location.
   - The SOS SMS feature enables users to quickly send an SMS with their GPS coordinates to a designated contact in case of danger, facilitating rapid assistance.

### 6. **Safety Tips (Survival Guide)**
   - A survival guide API provides users with step-by-step tips on handling various emergency situations, such as "How to Change a Tire" or "Basic First Aid."

### 7. **Settings (Language & Theme)**
   - Users can change the app language to Afrikaans, Zulu, or English, making it accessible to a broader audience.
   - Dark mode is available, following system settings for user comfort.

### 8. **Calendar Feature for Community Events**
   - SafeZone offers a list of community events that users can save to their personal calendar, keeping them engaged with local safety initiatives and gatherings.

### 9. **Logout**
   - Users can log out using the logout icon, securing their data.

---

## Design Considerations

- **User-Centered Interface Design**: With a focus on accessibility, SafeZone’s layout prioritizes simplicity, ensuring features are easy to access, especially in stressful situations.
- **Responsive Design**: The app adapts to various screen sizes, ensuring usability across multiple devices.
- **Minimalistic Design for Speed**: SafeZone is optimized for quick load times, reducing unnecessary graphics to ensure critical features, like the SOS button, are immediately available.

---

## Installation

To install SafeZone, download the APK file from the GitHub repository, transfer it to your Android device, and run it to complete the installation.

---

## Technical Specifications

- **Software**: Android Studio, Kotlin, JSON
- **Hardware Requirements**: 1.8 GHz 64-bit processor, 4GB RAM (minimum)
- **OS Requirements**: Android 10 or later

---
## user defined feature 4
Event feature , users can see all the events that are taking place in the community  

---
## user defined feature 5 
users can save the event to their local calanders on their phones 

---

## Frequently Asked Questions

**Q1: What is the main purpose of SafeZone?**  
A1: SafeZone helps users in South Africa detect and report crime. Users can add map markers to report crimes and send an SOS SMS with their location if in danger.

**Q2: How does the SOS SMS feature work?**  
A2: Users press the SOS button to notify a contact with their current GPS coordinates, aiding in locating them during emergencies.

**Q3: What customization options are available in the app?**  
A3: SafeZone offers language preferences (Afrikaans, Zulu, English), and a calendar for community events.

---

## Developer Contact Information

**Developer:** Alisa Diya Thool  
**Email:** ST10037089@vcconnect.edu.za  

**GitHub Repository:** [SafeZone Crime Detection](https://github.com/VCWVL/opsc7312-poe-alisadthool.git)

---

## Change Log from planning document and part 2 

- I have changed the name of my app from , ISPY to safe zone crime dection to ensure users download it for the name ispy can have a negeative connoation
  ![safe (1)](https://github.com/user-attachments/assets/69360c2d-8ea8-4f8a-ad5f-93c886a25129)

- I also changed the logo so it suits the name of my application .
- The colour scheme , use to be blue , now i have changed it a light brown and and grey based colour
- For my feature 4  ,orginally i wanted to use broadcast feature where on a seperate screen users will have acesss to all the crimes that we reported within a 30 days
  but i changed it to the comminuty event feature
- in my part 2 i implemneted a emergency contacts api , where users could see all the important contacts they should know , but in part 3 i implemnted my orginal idea from my planning document
  from part 1 , where i created a survival guide api , so its things users should know in emergency situtions like changing a tyre etc 
  
---
## References
• Deccon Tech (2024). Fingerprint biometric authentication. | Android Studio | KOTLIN 
2024. [online] YouTube. Available at: 
https://www.youtube.com/watch?v=5DIhS_kwva8  [Accessed 30 Sep. 2024]. 
• Android Knowledge (2023). Bottom Navigation in Android Studio using Kotlin | 
Android Knowledge. [online] YouTube. Available at: 
https://www.youtube.com/watch?v=KBtMFTjfzA0  [Accessed 30 Sep. 2024]. 
• Easy Tuto (2021). How to Integrate Google Sign In in Android | 2022. YouTube. 
Available at: https://www.youtube.com/watch?v=suVgcrPwYKQ [Accessed 30 Sep. 
2024]. 
• CodingSTUFF (2021). Fetching Movies List From API using Volley Library in Android 
Studio (2021). [online] YouTube. Available at: 
https://www.youtube.com/watch?v=r5TmVDdFgKE  [Accessed 30 Sep. 2024]. 
• CodingSTUFF (2021). Fetching Data From API using RETROFIT Library @GET in 
Android Studio (2021). [online] YouTube. Available at: 
https://www.youtube.com/watch?v=seuRVttjQdM  [Accessed 30 Sep. 2024].
•Glide library || Glide Library android studio tutorial || Kotlin || 2022 (2022) YouTube. Available at: https://youtu.be/9KjiXhGXdis?si=uzFuhE0l0iVxMK29 (Accessed: 24 April 2024).
•How to implement ScrollView in Android (2023) YouTube. Available at: https://youtu.be/K4CGYiQu52s?si=CcaEbO0VbDadDjc1 (Accessed: 29 April 2024). 
•Retrieve image from Firebase in Android app || Firebase Storage tutorial || android studio tutorial (2021) YouTube. Available at: https://youtu.be/DRqObCUCGl0?si=0ibTBcigKz33ofvV (Accessed: 24 April 2024). 
•Referencing How to Change App Icon in Android Studio | Android Beginner Tutorials -https://www.youtube.com/watch?v=m6qBOTjZ4Lw SIGN-IN WITH GOOGLE || FIREBASE || ANDROID STUDIO KOTLIN TUTORIAL || STEP BY STEP IMPLEMENTATION-https://www.youtube.com/watch?v=H_maapn4Q3Q&t=40s Android Studio Tutorial - Login and Signup Material Design Ui-https://www.youtube.com/watch?v=uMgW9SieElk&t=76s Build APIs with Ktor and Kotlin-https://www.youtube.com/watch?v=xKmLZ9cIWss


With SafeZone, staying safe is just a click away. Thank you for using our app to help make South Africa a safer place for all.
