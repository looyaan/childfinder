# childfinder
ChildFinder: A Digital Solution for Locating Missing Children
Introduction
ChildFinder is a mobile application designed to assist in locating missing children using modern technology. The application leverages geolocation services, secure user authentication, and real-time notifications to help parents and guardians track their children's whereabouts and receive alerts if they venture outside predefined safe zones.

Features
User Registration and Authentication: Secure user registration and login using Firebase Authentication.
Child Profile Management: Create, update, and manage profiles for missing children with essential details such as name, age, appearance, last seen location, and additional notes.
Geolocation and Safe Zones: Track the child's location using the device's GPS and define safe zones. Receive notifications if the child moves outside these areas.
Real-Time Notifications: Receive alerts and updates through Firebase Cloud Messaging.
System Architecture
The application is built using Flutter and integrates with Firebase for backend services. The key modules include:

User Interface Module: Manages the user interface components.
Registration and Authentication Module: Handles user registration and authentication.
Child Profile Management Module: Manages the child profile data.`
Geolocation and Safe Zones Module: Tracks the child's location and manages safe zones.
Notification Module: Sends real-time notifications to users.
Dependencies
The project uses the following dependencies:

firebase_core
firebase_auth
cloud_firestore
firebase_messaging
geolocator
flutter_local_notifications
http
Installation
o set up the project, follow these steps
Clone the repository
git clone https://github.com/looyaan/childfinder.git
Navigate to the project directory
cd childfinder
Install the dependencies:
flutter pub get
Set up Firebase:

Add your Firebase project configuration files (google-services.json for Android and GoogleService-Info.plist for iOS) to the respective directories.
Run the application:
Usage
Register or Sign In:

Users can register a new account or sign in to an existing account using their email and password.
Create Child Profiles:

After signing in, users can create and manage profiles for missing children by providing necessary details.
Track Location:

The app tracks the child's location using GPS and displays it on a map. Users can define safe zones for their children.
Receive Notifications:

Users receive real-time notifications if the child leaves the safe zone or if any new information is available.
System Testing and Performance
The application underwent thorough testing, including unit testing, integration testing, and system testing, to ensure reliability and performance. User feedback and performance metrics were collected to evaluate the system's effectiveness and identify areas for improvement.

Future Enhancements
Future enhancements could include:

Improving the user interface for better usability.
Adding more data sources for better accuracy in tracking.
Integrating real-time video streaming from the child's location.
Implementing advanced analytics for tracking movement patterns and predicting potential locations.
Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
Contact
For more information, please contact:

Author: omar musse and abdalla Ahmed
