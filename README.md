# Assignment 2: Simple Interactive App
## Objectives
Successfully create an Android project in Android Studio that utilizes Jetpack Compose and Kotlin to present a UI and then update the UI state in response to user interaction.

## Tasks
- Create a customized implementation of a subset of the following project in Part 3 of Unit 2 of Android Basics with Compose: Create an Art Space app Links to an external site.
    - Be sure to consult the course materials for help as needed
- Your app needs to display the information shown in the sample screen shot in Step 1 ("Before you begin") with the following changes:
    - The exact layout use does not have to be "pixel perfect" to the one in the codelab, but it must have the same elements, grouped in a similar layout (see demo video for a functional example)
    - For the top line of text below the image, display the message "Current count: X" where X is the current count value
        - The count value starts at 3 and must range between 1 and 5 (inclusive)
    - For the text beneath the current count:
        - Have your name (first and last, as shown in Canvas) for the bolded text
        - Put CS 492 in the parentheses after the bolded text
    - The image will not change for the purposes of this assignment
        - You can use any image in good taste you choose, including the Android image from Assignment 1
    - The text and background color can be whatever you choose, as long as they are easy to read
- Your app needs to (only) implement the following interaction:
    - When the Next button is pressed, the current count increments by 1. If it goes over 5, it needs to be reset to 1
    - When the Previous button is pressed, the current count decrements by 1.  if it goes below 1, it needs to be reset to 5
- When you have implemented the app with these changes, run it on an Android emulator and record your screen per the instructions below.
    - Once recorded, upload your demo video per the instructions provided (provided link highly recommended)

The app has to run without crashing.

## Notes
This is meant to be a very focused assignment.  The relationship between the UI and state is a very important topic that we will be exploring in future units.  Look for examples of similar functionality that you've implemented in other codelabs that will assist you in implementing this assignment.

Also, please be aware that when writing code, naming files, etc. it is crucial that everything be to specification.  Please know that any deviation from the instructions on any work in this course, however small, will lead to a deduction.

## What to turn in
Highly recommended:  Tips and Guidance for Video Submissions (Jack Barnes)

When complete, submit a video recording of your computer screen that includes all of the following:
1. Code editor displaying a part of the app’s codebase. 
    1. Have a visible comment block in the displayed code file that displays (in a clean easily readable manner):
        1. Your name
        2. OSU
        3. CS 492
    2. Do a quick scroll through the entirety of the MainActivity.kt code
2. The app already running in the emulator.
3. A display of interaction to include:
    1. Hitting Next three times to increment the value to 5, then the wraparound back to 1
    2. Hitting Previous once to demonstrate the wraparound from 1 back to 5.

This video for this assignment should not be longer than 60 seconds, but only needs to be long enough to show all of the required elements.

Use the same format demo as shown for Assignment 1.  Here's an example of a functional demo:

## Grading criteria
Be sure to consult the rubric for expectations regarding your submission.

## Extensions
Want to do more? Try the following extra challenges.
1. Implement other elements shown in the provided codelab, such as multiple images, titles, etc. that you can step through
2. Try out some different layouts and note what changes you needed to make in your Composable functions to achieve this
3. As you explore the next unit, implement a data class to represent the images and their related data
