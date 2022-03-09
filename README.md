# Text-Editor-PWA

## Table of Contents
- [Description](#description)
- [Authors](#authors)
- [Github Link](#github-link)
- [Installation](#installation)
- [Usage](#usage)
- [Video Walkthrough](#video-walkthrough)
- [How to Contribute](#contribute)
- [Resources](#resources)


## User Story 
```
- As a Developer
- I want to create a text editor application that can be used to create notes or code snippets with or without internet connection
- SoThat I can retrieve the information and use the applicaiton anywhere.
```
## Description
This project takes in an existing text editor application and adds ofline functionality by adding additional features to make it as a PWA or also called "Progressive Web App". These applications are built with the same web technologies as normal websites but feel and function like an a native app.

The things I learned while adding the additional PWA features to this exisiting text editor app was the basics of how PWAs work and the necessary components that are necessary for it to function offline. The most difficult aspect of this project was remembering and correctly implementing the necessary  components into the application such as correclty creating a service worker  or installing the correct  dependencies in the correct location. Once I throroughly read the webpackk documentation, I was able to complete the application. 

## Author 
- Takara Truong

### Github Link
* https://github.com/truont2/Text-Editor-PWA

### Heroku Link
* https://pwa-jate-text-editor-tt.herokuapp.com/

## Installation

To install this application:
1. clone the necessary files in the github repository by going [here](https://github.com/truont2/Text-Editor-PWA).
2. Open VSCode up the terminal in the index.js file where you will run the code below. This will install the necessary packages needed to run this application. 
```
npm install
```
3. Next run the following commmand 
```
npm run start:dev
```
4. Then run the snippet below to start the application
```
npm run start
```
5. THen in your brower, enter the following link to reach the application
```
http://localhost:3000/
```
## Usage

* The application will load a screen presented with a install button and a section to enter text
* Users will be able to enter text onto the screen and the text will stay on the application
* Users will addititonally be able to install the application using the install button on the top left of the application screen
* A desktop icon will appear on the users desktop allowing the application to be used offline

### Video Walkthrough: 

This video shows the functionality of the application
## Contribute

To contribute, contact me at https://github.com/truont2/ or truont2@gmail.com

## Resources 

* https://webpack.js.org/
