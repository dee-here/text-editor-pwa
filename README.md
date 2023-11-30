# JATE Text Editor Progressive Web Applications (PWA)
![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)  


## Description 
[Deployed app](https://ds-text-editor-pwa-4262863a72d2.herokuapp.com/)

This project was to build a text editor that runs in the browser. This application is a single page application that meets the PWA criteria and is deployed to Heroku at the link under description.

This app can be be used to create code snippets or notes with or without an internet connection.

It uses multiple data persistence techniques to handle browser compatibility. This application can also be used while being offline.
It can also be downloaded to your desktop as an application.


## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |-------------| 
| JavaScript    | [https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) | 
| node.js    | [https://nodejs.org/en](https://nodejs.org/en) | 
| Express.js    | [https://expressjs.com/](https://expressjs.com/) |  
| idb | [https://www.npmjs.com/package/idb](https://www.npmjs.com/package/idb)     |  
| webpack | [https://www.npmjs.com/package/webpack](https://www.npmjs.com/package/webpack)     |  
| Babel | [https://www.npmjs.com/package/Babel](https://www.npmjs.com/package/Babel)     |  
| Git | [https://git-scm.com/](https://git-scm.com/)     |  


Idb package was used as a wrapper around an IndexedDB database. It provides useful features for storing and retrieving data. OpenDB function from idb was used to get and update data from the database.

Babel was used to seamlessly load different types of files for this application.  

Webpack was used as a module bundler. Its main purpose is to bundle JavaScript files for usage in a browser. It is also capable of transforming, bundling, or packaging just about any resource or asset.


## Installation 
Run the command `npm run start` in a terminal at the root directory to start the application.  
This starts up the backend and serves the client to a browser.


## Screenshot
![JATE Text Editor](./Assets/00-demo.gif)


## Author Info

Deepak Sinha
* [Portfolio](https://dee-here.github.io/portfolio/)
* [Github](https://github.com/dee-here)
* [Questions ](mailto:deepakdilse@gmail.com)

## License
![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)  

[License Link](https://choosealicense.com/licenses/mit/)  
