# Dosely – Initial Project Definition

## 1. What Problem Am I Solving?

People who take medication may forget to take their doses or have difficulty keeping track of their medication schedules.

## 2. Who Are My Users?

Dosely is designed for people who take medication regularly, either short-term or long-term, and need a simple way to manage their medication schedules and receive reminders.

## 3. How Do I Want to Solve the Problem? (MVP)

The Minimum Viable Product (MVP) will be an Android mobile application that allows users to:

* Add, edit, and delete medications.
* Set medication schedules and reminders.
* Receive local notifications when it is time to take medication.
* Mark scheduled doses as taken or missed.

All medication data will be stored locally on the user's device.

## 4. What Will Not Be Included in the MVP? (Non-Goals) – And Why?

* **User registration and login:** The application is intended for individual use and does not require user accounts.
* **Cloud storage and synchronization:** Local storage is sufficient for the initial version and reduces implementation complexity.
* **iOS support:** The initial version will target Android only to keep development focused.
* **Integration with pharmacies or healthcare providers:** External integrations are not necessary for the core medication management functionality.
* **Automatic medication recommendations or dosage calculations:** The application will help users manage their medication routines, not provide medical advice.
* **Barcode scanning and medication identification:** These features are not essential for the initial version.
* **Dose history and advanced statistics:** The MVP will focus on managing medications and tracking scheduled doses without maintaining historical records or generating reports.

## 5. What Technologies Do I Need?

* **Kotlin:** The programming language for developing the Android application.
* **Android Studio:** The development environment for building, running, and debugging the application.
* **Jetpack Compose:** The toolkit for building the application's user interface.
* **Room (SQLite):** Local database storage for medication details and schedules.
* **Android Notifications and AlarmManager:** Android APIs for scheduling medication reminders and displaying notifications, subject to system permissions and restrictions.
* **Git and GitHub:** Version control and hosting the project's source code and documentation.

The application will be developed for Android and will not require a backend server or an internet connection for its core functionality.
