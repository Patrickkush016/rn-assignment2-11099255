# rn-assignment2-11099255

11099255

Objective

My goal is to create a straightforward React Native application that presents a styled text message on the screen, distinguishing a name with a unique style. Additionally, the application will feature a status bar with default styling.

Steps and Components

Importing Dependencies

I'll begin by importing StatusBar from expo-status-bar, React from react, and the necessary components (StyleSheet, Text, View) from react-native.

Main Application Component

I'll develop a default functional component named App. Inside this component, I'll return a View component styled with a predefined container style. Within this View, I'll include a Text component displaying the message "My name is", followed by another Text component presenting "Lawrence Adjei" with distinct styling. Furthermore, I'll ensure to incorporate the StatusBar component with its style set to "auto".

Styling

To style the components effectively, I'll define a StyleSheet with the following specifications:

container: This style will make the View occupy the entire screen, aligning its children both vertically and horizontally, and setting the background color to a specific green shade (#317d45).
nameText: This style will adjust the font size of the text to 24.
myName: This style will emphasize the name by setting its font weight to bold, distinguishing it from the surrounding text.

Expected Outcome

Upon running the application, it should exhibit a centrally positioned message against a green background, presenting "My name is Patrick Kushigbor" with "Patrick Kushigbor" displayed in bold. Additionally, the status bar should be visible with default styling.
