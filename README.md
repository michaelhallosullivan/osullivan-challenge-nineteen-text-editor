# osullivan-challenge-nineteen-text-editor

## User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Acceptance Criteria
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

## Description

Students are tasked with building a text editor that runs in the browser. It will be an offline-functional progressive web application (PWA) with a single page and include an IndexedDB database.

## Installation

Npm i
Npm run build


## Usage

This text editor can be used to practice writing code or jot down ideas without interfering with the code in your directories. Written code can be saved and referred to later and the text editor can even work offline for enjoyable coding off-the-grid.

Video Walkthrough - (https://drive.google.com/file/d/1ciCo5Dv9bZ3qARBkjiQaAWprOR_aTEn6/view)

## Credits

Starter code by UC Berkeley. Additional code written by Michael O'Sullivan.
Node
IndexedDB
Webpack
Nodemon
Babel
---Additional here---

---template---
 Used Node.js (https://nodejs.org/en) and MongoDB (https://www.mongodb.com/). Used node packages Mongoose (https://www.npmjs.com/package/mongoose), Express (https://www.npmjs.com/package/express), and Nodemon (https://www.npmjs.com/package/nodemon).

## License

MIT License

---insert photo here when done--
![Model](https://github.com/michaelhallosullivan/osullivan-challenge-eighteen-social-network/blob/main/examples/challenge-eighteen-screenshot.jpg)