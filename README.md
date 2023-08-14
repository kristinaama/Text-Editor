# 19 Progressive Web Applications (PWA): Text Editor

  ![License](https://img.shields.io/badge/license-MIT-green)

## Table of Contents:
  1. [Description](#description)
  2. [Installation](#installation)
  3. [Usage](#usage)
  4. [Contributions](#contributions)
  5. [Tests](#tests)
  6. [License](#license)
  7. [Questions](#questions)

## Description:
 The objective of this application is to build a text editor that runs in the browser. As a developer, I want to create notes or code snippets with or without an internet connection so that I can reliably retrieve them for later use. The app is a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

The following acceptance criteria were kept in mind when developing this application:

 ```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

  The following screenshots demonstrate the functionality of the web application.
  Website user interface:
<img width="1280" alt="JATE" src="https://github.com/kristinaama/Text-Editor/assets/127279859/4c0d81c9-8629-42b4-8cb8-ec1c96221fb4">

  IndexedDB:
  <img width="1266" alt="JATE - IndexedDB" src="https://github.com/kristinaama/Text-Editor/assets/127279859/e9dcccc0-1164-42c0-bb84-0a5ac68666c0">

  Manifest:
  <img width="1267" alt="JATE - Manifest" src="https://github.com/kristinaama/Text-Editor/assets/127279859/b0bf1db4-a142-4279-b753-de2bb77756d2">

  Service Workers:
  <img width="1266" alt="JATE - Service Workers" src="https://github.com/kristinaama/Text-Editor/assets/127279859/e2d5714e-ddd0-4ac0-93de-98668c1332fa">

## Installation:
 The code can be downloaded via the Text Editor folder on my Github page.

## Usage:
  This Text Editor is intended for easy navigation by using deployed webpage.
  
  Alternatively, the user can download the files on the Text Editor Github repository, running 'npm install' in the command line in the installed directory, and then running 'npm run start'. The user can then access the application on their localhost:3000 webpage.
  
## Contributions:
  Samantha Rudolph - UC Berkeley Extension Instructor

## Tests:
  No tests were recorded for this project.

## License:
 This project is licensed under the terms of the MIT license.

## Questions:
  Please refer to the following Github profile link: https://github.com/kristinaama.
    For any additional questions, please e-mail kristina.mae.ama@gmail.com.
