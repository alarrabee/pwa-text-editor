PWA Rreadme

U of M Boot Camp Module 19 Challenge

# Description
This is the week 19 Module Challenge for the U of M Coding Bootcamp

# Progressive Web Applications (PWA): Text Editor
The challenge was to build a text editor that runs in the browser from starter code. The app will be a single-page application that meets the PWA criteria and feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline. 

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

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
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```

## Link to Deployed Application
[Link](https://pwa-text-editor-tlha.onrender.com)

## Application Screenshots
![image](https://github.com/user-attachments/assets/b25dc5a7-93fa-4172-8c1b-6483cc3f24fa)

## Challenges
Unable to start a development server due to an error stating application was compiled with errors. Was not able to fix this error and application was not able to be successfully deployed.
