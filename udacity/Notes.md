# Notes During Learning
## Lesson Plan
### Lesson 1: Create Project Sunshine with a Simple UI (5-8 hrs)
Starting by installing Android Studio, youíll create your first project with a simple list-based user interface and built and deploy it to virtual and actual devices. 
Youíll also discover what makes mobile - and Android in particular - a unique environment for app development.
- Android Studio, Gradle, and debugging tools
- User Interface and Layout managers
- ListViews and Adapters

### Lesson 2: Connect Sunshine to the Cloud (8-10 hrs)
Replace the mock data with real weather data by connecting Sunshine up to an Internet back-end courtesy of the Open Weather Map API. 
Youíll learn how to add permissions to your app, initiate network I/O, and how to move time consuming tasks like network data transfers off the main UI thread.
- Threading and ASyncTask
- HTTP requests on web APIs
- Android Permission System
	
### Lesson 3: Create New Activities and Navigate Apps with Intents (8-10 hrs)
Give your app structure and create more complex Activities. Youíll learn about Androidís Intent framework, and how to use Intents to navigate between Activities, both within your app and as a way to add 3rd party functionality.
- App navigation with Explicit Intents
- Implicit Intents to incorporate 3rd-party apps
- Share Intent and the Android sharing framework
- Broadcast Intents and Broadcast Receivers

### Lessons 4: Use Content Providers and Loaders to Persist and Recover Data (15-20 hrs)
Learn how the Android framework manages the activity lifecycle, and how it differs from what you might expect, and dive head-first into the world of persistent storage. 
Learn how to create databases, use Android's Content Providers to provide an abstraction layer between your data and your UI implementation, and use Loaders to efficiently load stored data.
- Activity lifecycle and background activity termination
- SQLite databases and JUnit tests
- Creating and using a Content Provider as an abstraction layer
- Using Loaders to asynchronously load data
- Creating Adapters to bind UI components to Content Providers
	
### Lesson 5: Implement Rich and Responsive Layouts (8-10 hrs)
Create rich, responsive user interfaces that work across a variety of different hardware types and screen sizes. 
You'll learn more details on using the Android Layout managers, Fragments, UI widgets, and Android design principles to add visual polish to your user interfaces, and how to create your own controls from scratch.
- Fundamental Android design principles
- Supporting localization and variable screen sizes
- Optimizing tablet UIs using Fragments
- Accessibility Features
- Custom views
	
### Lesson 6: Use Services and Notifications to Run in the Background (5-8 hrs)
Deliver a great user experience, even when your app is not visible. 
Learn how the Android framework manages background apps; and discover how to use Services and Notifications to make your app to be active when it's not in the foreground. 
You'll learn techniques for efficient data transfers using SyncAdapters and Google Cloud Messaging, so your app can stay up-to-date without draining the battery.
- Background services and alarms to schedule background tasks
- Efficient background data transfers with SyncAdapters
- Rich notifications to interact with users
	
### Final Project (10-20 hours)
Build your own Android app incorporating the skills you've learned in this course.

## Lesson Note
### Lesson 1
#### Android Software Stack
Linux Kernel->C/C++ Libs|Android Runtime->Application Framework->Application Layer
#### gradle
```
./gradlew tasks
```