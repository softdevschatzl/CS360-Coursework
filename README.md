# CS360 Event Tracker App

This project involved the design and development of the Event Tracker App,a mobile application created 
to help users manage their events efficiently. The app addresses the need for individuals to track personal 
or professional events. The primary goal of this project was to develop a functional, user-friendly mobile 
app that reflects both best practices in mobile development and user-centered design principles. 

### Requirements and Goals
The Event Tracker App was developed to meet the following requirements:

Allow users to create, edit, delete, and view events.
Store event information such as the name, date, location, and description.
Provide SMS notifications for event reminders (simulated in the emulator).
Offer a simple, intuitive user interface that supports both beginners and experienced users.
The app addresses a common user need to stay organized and keep track of upcoming events with minimal effort. It ensures that users can access their event data offline and receive timely reminders.

### UI Design
The app’s UI design focused on simplicity and usability:

Screens: The app includes key screens such as the MainActivity, LoginActivity, DataDisplayActivity, and SMSNotificationActivity. Each screen serves a specific purpose, ensuring a smooth user experience.
User-Friendly Features: The interface was designed with easy navigation, ensuring users can add and edit events quickly. The RecyclerView presents events clearly in a list format, and each event includes a delete button to remove outdated entries effortlessly.
Accessibility: Minimalist icons and a clean design were used to reduce clutter and enhance readability.
These design choices ensured that the app met user expectations and provided a consistent, enjoyable experience.

### Development Strategies
The development process started with a planning phase, followed by UI design and the gradual implementation of features. The following strategies were employed:

Modular Coding: Breaking the app into components such as individual activities, adapters, and helper classes to make the code more manageable.
Version-Specific Logic: Handling SMS functionality with different implementations for Android 12+ and older versions.
Database Management: Using SQLite for persistent storage to ensure that event data is available even if the app is closed.
These strategies ensured the project was completed efficiently and could easily be expanded or modified in the future.

### Testing Process
Testing was conducted throughout the development process to ensure the app's functionality. The Android Emulator was used to simulate the app’s behavior on different devices. Key tests included:

Functional Testing: Verifying that all CRUD operations (Create, Read, Update, Delete) for events worked correctly.
Permission Handling: Ensuring that SMS and phone state permissions were correctly requested and handled.
Error Handling: Adding validation to prevent empty input fields and ensure smooth user interaction.
This process was critical to uncover minor bugs and optimize the user experience. It confirmed that the app met the functional and performance goals outlined during the planning phase.

### Challenges
One of the challenges I faced was ensuring that permissions were properly handled within the application. I had to ensure that not only proper permissions were granted,
but to also persist these changes was often a tough task.

### Key Achievements
My favorite aspect of this app is the simple, in-memory SQLite implementation, which allowed for proof of concept without the added complexity of an entire SQL instance connected to the application.
Displaying proficiency with database applications in this way proved to be very satisfying as database implementation is one of the most important aspects of application development.
