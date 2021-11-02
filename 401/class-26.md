# Android Fundamentals
`"The Android system implements the principle of least privilege. That is, each app, by default, has access only to the components that it requires to do its work and no more. This creates a very secure environment in which an app cannot access parts of the system for which it is not given permission"`[**Source Link**](https://developer.android.com/guide/components/fundamentals)
 
###~ There are four different types of app components:
* Activities
    - they are what the user interacts with
    - keep track of what the user is interacting with
    - provide a way to "share" content within the app

* Services
    - keeps the app running in the background for various reasons

* Broadcast Receivers
    - low battery notifications
    - upcoming schedule event
    - any other system-wide broadcast announcements

* Content Providers
    - manages a shared set of app data you can persist
    - can query or modify the data if provider allows it
    - can read and write data that is private to your app

### Activating Components
`"Three of the four component types—activities, services, and broadcast receivers—are activated by an asynchronous message called an intent. Intents bind individual components to each other at runtime. You can think of them as the messengers that request an action from other components, whether the component belongs to your app or another."`[**Source Link**](https://developer.android.com/guide/components/fundamentals)

An intent has two types; 
- Explicit intent, which activates a targeted component. 
- Implicit intent, activates a specific type of component.

Three of the four app components are activated using the class **`Intent`**.  Broadcast receivers are not activated using intent, they instead use a request called a **`ContentResolver`**

You must declare all app components using the following elements:

- `<activity>` elements for activities.
- `<service>` elements for services.
- `<receiver>` elements for broadcast receivers.
- `<provider>` elements for content providers.

##### Additional information may be found on the Android developers guide [**Android Fundamentals**](https://developer.android.com/guide/components/fundamentals)

[Back to Main Page](../README.md)
