# AR-VR-Video-Player
This Android application, built using Unity, is designed for use with Google Cardboard or other compatible VR headsets. It enables video projection and playback on real-world images or objects.

The app was developed using the Unity Engine in combination with the Vuforia SDK, which facilitates image and object tracking. I utilized the Vuforia database to upload and manage the images used for tracking. Vuforia provides a Unity-compatible package for these images/objects, allowing them to serve as tracking targets within the application.

A custom C# script was written to override the default tracking behavior. This script enables the video to automatically play when the target is detected in view and pause when tracking is lost.

Additionally, the Android SDK was integrated to build and install the app on my Android device.
