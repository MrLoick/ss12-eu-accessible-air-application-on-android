# Problem Description #

Many up-to-date mobile applications are designed and implemented in “Action Script” and published within the Adobe Air Runtime. This runtime provides poor accessibility on all mobile platforms, making it impossible for blind people to operate what leads to a deadlock situation because even developers that want to make their apps accessible for blind people do not have a chance to do this in reasonable time.

To deal with this issue, we want an Adobe Air Framework for Android that uses the Android Text to Speech Engine in order to give blind users information on controls that are currently on the screen upon touch. After touching this specific element a second time, it should be triggered.

To reach basic functions like “Text to Speech” of Android, a native extension for the air-runtime needs to be developed. Creators of Air Applications should be able to use the framework within their applications, and as long as they use standard controls like buttons and labels for their GUIs also blind people should be able to interact.

# What has been implemented #

  * A native extension for the Adobe AIR Runtime allowing the usage of the Android Text-To-Speech functionality
  * A library that parses UI-Elements within Air-Applications, handles user interaction and uses the Text-To-Speech functionality of the native extension in order to enable blind people to operate Air-Applications that are normally completely inaccessible for them.
  * A demo application to show the functionality of the library.