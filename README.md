# AccomplisherApp
This App demonstrates how to write a mobile app with backend data storage, real-time synchronization, and email notifications using Firebase and Google App Engine.

Note: This is one design pattern for building mobile services on Google Cloud Platform. For a comparision of your other options,
See Build mobile apps using Google Cloud Platform .
The instructions show how to do this using:

Firebase — a powerful platform for building iOS, Android, and web-based apps, offering real-time data storage and synchronization, user authentication, and more.
Android Studio — an Android development environment based on IntelliJ IDEA.
Cloud Tools for Android Studio — a set of tools, included with Android Studio, that provide integration with Google Cloud Platform services.
App Engine — an environment for running application code in the cloud; Platform as a service (PaaS).
The sample app stores a to-do list in Firebase, which automatically synchronizes the data across devices, and then uses backend logic running on App Engine to send out daily reminder emails.
By connecting App Engine to a Firebase database, you can perform complex logic on data without having to manage synchronization and updates; Firebase handles that for you.

