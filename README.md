# Instant placement
## About Project
The Instant Placement API allows the user to place AR objects instantly, without having to first move their device to allow ARCore to establish full tracking and detect surface geometry. This app renders and instant 3d model on overlapping with camera capture using Augmented reality.
## Installation steps-
There are some following steps 
- Api level should be Api 24 -Android 7 or above. Android Studio version Should be 3.1 or higher for Augmented Reality Apps.
- In build.gradle of App, add a sceneform UX library and Sceneform Assets library.
- Compile Option to support Java which is needed for Sceneform library.
- In Android Manifets.xml file add permission for AR features in app, Camera permission, Internet permission add meta data to make it available for "Google Play Services for AR".
- Add the fragment as shown which is provided by Sceneform ux library.
- Install google sceneform tools (beta) plugin from android studio only.
- There is one setting icon on left side of screen when we select instant placement option and than enable it than you will see instant 3d model object on the screen.
- In this project we have used various class to show the instant placement.
- Write down the code in MainActivity as shown in the tutorial.
- Run the App.
- 
## Libraries/Dependencies with their versions :
- [Sceneform](https://developers.google.com/sceneform/develop)- Sceneform is a 3D framework that makes it easy for you to build ARCore apps without OpenGL. We are using 1.15.0 version of google.ar.sceneform.ux:sceneform-ux.
	
## Permissions :
- We are using [Camera permission](https://developer.android.com/guide/topics/media/camera), [Internet permission](https://developer.android.com/training/basics/network-ops/connecting) and [hardware.camera.ar permission](https://developers.google.com/ar/develop/java/enable-arcore).

## Output will be
You will see the 3d model on the plain surface.
- ![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/78479435/127740790-16bfc993-f30c-46f3-a79b-58ea9ab577fc.gif)

## Difficulties faced while working on project
- Faced difficulties in installing [Google senceform (beta) plugin](https://plugins.jetbrains.com/plugin/10698-google-sceneform-tools-beta-).

## Overcome the difficulties
- Tried installing various versions of Android API to support Google senceform (beta) plugin.

## Tried to do but not succeed
We tried to show the model instantly without interacting with the screen but was not possible at that time.

## Future plan regarding the development of project
Our future planning about this project is to control the movement of 3d model with touchless hand gestures just by moving the fingers or hand without touching the screen.
