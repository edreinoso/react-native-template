# React Native Template

### Goal

Make React Native application set up easier to get started.

### Motivation

It was really difficult in the beginning to start developing in the React Native due to the complexity of setting up config files in both Android Studio and XCode. Howerver, Expo has really made this a lot easier by providing a wrapper where React Native can run, releasing the burden of managing the configuration and extra activities.

Having this template has helped me cut down time in getting started with react native applications since it is easily reproducible and adaptable to whatever need is required.

### Tech stack description

- Language: Javascript
  - Framework: React Native

- State Management: Redux

- Libraries:
  - React-Navigation
  - React-Redux

### Directory Structure

The src directory is where the code is going to be located. This directory is divided by the following:
- Components: will have all components of application, such as Buttons, Text Fields, Text Inputs, etc

- Navigation: will be using React-Navigation library to handle the application navigation

- Screen: will have the code for the frame screens

- Store: will have the state management using Redux

- Styles: will have styles such as text-size, color, font-type, etc.

- Utility: will have methods for validating input fields, making sure they pass the requirements set by the methods.
