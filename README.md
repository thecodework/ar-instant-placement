# Instant placement
## About Project
This app renders and instant 3d model on overlapping with camera capture using Augmented reality.
## What we have done ?
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

## Output will be
You will see the 3d model on the plain surface.

## Difficulties faced while working on project
- Google senceform (beta) plugin was installing .
- various class and libraries

## Overcome the difficulties
- Installed android differnt version.
- Dependencies should be properly saved.

## Tried to do but not succeed
We were trying to show instant model with out touching the screen but we are not able to do it.

## Future plan regarding the development of project
Our future planning  about this project is to move the 3d model with touchless just moving the fingers or hand from long without touching the screen.