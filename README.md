[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Title: PWA: Text Editor

## Description:
This PWA application is a text editor that runs within the browser. Which also will automatically be installed when hitting the install button on the left corner of the screen. This application also runs on offline, meaning no network needed to use it. This application utilizes the help of an "indexedDB" which is a type of database for storing data by mutliple key types. This application is easy and clean viewing for any user looking to create notes with or without internet. That you can retrive right from your computer's local after installation. 

## Table of Contents

- [Title](#title)
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Github Repo Link](#github-repo-link)
- [Deployment from Render Link](#deployment-from-render-link)

### User Story:

AS A developer

I WANT to create notes or code snippets with or without an internet connection

SO THAT I can reliably retrieve them for later use


### Acceptance Criteria:

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

WHEN I deploy to Render

THEN I should have proper build scripts for a webpack application



### Github Repo Link:

https://github.com/scerda8/PWA-Text-Editor.git

### Deployment from Render Link:

https://pwa-text-editor-gdwt.onrender.com
