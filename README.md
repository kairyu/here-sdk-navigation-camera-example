# HERE SDK Navigation Camera Example

Modified based on [HERE SDK 4.x - Navigation Example for Android](https://github.com/heremaps/here-sdk-examples/tree/master/examples/latest/navigate/android/Navigation), for showing how to change camera tracking mode with [VisualNavigator.setCameraBehavior](https://developer.here.com/documentation/android-sdk-navigate/4.13.0.0/api_reference/com/here/sdk/navigation/VisualNavigator.html#setCameraBehavior(com.here.sdk.navigation.CameraBehavior)).

---

The Navigation example app shows how to calculate a route from A to B and how to start turn-by-turn navigation with voice commands. You can find how this is done in [NavigationExample.java](app/src/main/java/com/here/navigation/NavigationExample.java). It also shows how to set a tracking view when navigation is stopped.

Build instructions:
-------------------

1) Copy the AAR file of the HERE SDK for Android to your app's `app/libs` folder.

Note: If your AAR version is different than the version shown in the _Developer's Guide_, you may need to adapt the source code of the example app.

2) Open Android Studio and sync the project.

Please do not forget: To run the app, you need to add your HERE SDK credentials to the `MainActivity.java` file. More information can be found in the _Get Started_ section of the _Developer's Guide_.
