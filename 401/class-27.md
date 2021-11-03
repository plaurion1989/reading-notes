# Intents, Activities and SharedPreferences
## SharedPreferences
* Get a handle to shared preferences:
  - Using `getSharedPreferences()` if you need multiple shared preference files identified by name, calling this from any `Context` in the app.
  - `getPreferences()` is used from an `Activity` typically if you only need one shared preference file
* Write to shared preferences:
    - You will need to create a SharedPreferences.Editor, Passing the keys and values you want with methods like `putInt` and `putString`
    - saving your changes can be done asynchronously using `apply()` or synchronously with `commit()`
* Read from shared preferences:
    - Simple as calling a method like `getInt` or `getString` then providing the key to get your desired value
    - A default value you set can return if key isn't present

## Tasks and the back stack
Definition: 

- A `task` is a collection of activities that a user would interact with on your app to try and do something.
- The `back stack` are activities that are arranged in a stack placed in the order they were opened.
- `root activity` is the first activity in the task's back stack, all other activities will be added to the stack as the user interacts with the app.

##### Lifecycle of a task
Let's say that an activity named `Activity A` starts based on user selection of said activity (is not root activity).  When in `Activity A` the user starts a new activity, this is usually done when the user goes to another part of your application.  `Activity A` will stop, but the state will be retained (where you are on the page, text entered, etc.) before it starts `Activity B`.  When the user presses the back button while in this new activity, `Activity B` is popped from the back stack destroying itself in the process, while `Activity A` resumes at the last known state.


[Back to Main Page](../README.md)
