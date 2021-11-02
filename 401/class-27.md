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

[Back to Main Page](../README.md)
