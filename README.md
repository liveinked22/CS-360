# CS-360
CS-360 Mobile Architect and Programming

## Weight Tracker Application Reflection

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of this project was to develop a fully functional Android application that allows users to track their daily weight and work toward a goal weight. The app includes user account creation, secure login, a database for storing weight entries, and SMS notifications when a user reaches their goal weight. The app was designed for people who want a simple way to record their progress over time without needing a complicated fitness application.

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application includes a login screen where users can create an account or sign in, and a dashboard where they can enter their current weight, set a goal weight, and manage their saved weight entries. The dashboard also allows users to update or delete previous entries. I kept the user interface simple by grouping related information together and making the buttons easy to find. This made it easy for users to move through the app without unnecessary steps, which helped create a more user-friendly experience.

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached the project by developing one feature at a time instead of trying to build everything at once. I started with the user interface, then added the SQLite database, login system, CRUD operations, and finally the SMS notification feature. Breaking the project into smaller tasks made it much easier to find and fix problems as they came up. This is a strategy I plan to continue using because it makes larger software projects easier to organize and maintain.

### How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the application throughout development using the Android Emulator. I verified that users could create accounts, log in successfully, add new weight entries, edit existing entries, delete entries, and save information in the SQLite database. I also tested both allowing and denying SMS permissions to make sure the application continued working correctly in either situation. Regular testing helped identify issues early and confirmed that each feature worked correctly before moving on to the next one.

### Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of the biggest challenges was connecting all of the different parts of the application together. The login system, SQLite database, dashboard, and SMS notifications all depended on each other, so I had to carefully organize the project and troubleshoot problems as they appeared. Breaking the application into smaller pieces allowed me to focus on one feature at a time, making the overall development process much more manageable.

### In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think the strongest part of my application is the database implementation. Creating a SQLite database that supports user accounts along with full CRUD functionality for weight entries demonstrates my understanding of Java programming, database management, and Android application development. I also gained valuable experience working with runtime permissions, activity navigation, and designing a user interface that is simple, organized, and easy to use. Overall, this project helped reinforce many of the concepts covered throughout the course and gave me a better understanding of the complete mobile application development process.
