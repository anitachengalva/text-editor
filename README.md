
# Text Editor

## Description

This project is a single-page Progressive Web Application. A pre-existing text editor application has been modified to function offline, using the [IndexedDB API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API), [idb npm](https://www.npmjs.com/package/idb) wrapper for [IndexedDB API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API), and a service worker using [Workbox](https://developer.chrome.com/docs/workbox/) to store data.


## Deployed Link

This application is deployed through Heroku.   

> https://akc-text-editor.herokuapp.com/


## Table of Contents

- [User Story](#user-story)
- [Installation and Usage](#installation-and-usage)
- [Technologies Utilized](#technologies-utilized)
- [Screenshots](#screenshots)
- [Contributors](#contributors)
- [License](#license)


## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```


## Installation and Usage

In order to run this application, you will want to `git clone` this repository so that the code is on your local machine. Run `npm i` while in the root directory in order to install all necessary [Node.js](https://nodejs.org/en/) dependencies. Then run `npm start` to launch the server.

This application is hosted at Port 3000, so typing: `http://localhost:3000/` in to the address bar of your browser while the server is running should display the user interface.

Hitting the "Install!" button allows you to save changes to the text editor regardless of whether you are online or offline. You are able to make changes, exit the application, and come back to your saved work.

## Technologies Utilized

> [Javascript](https://www.javascript.com/)

> [Node.js](https://nodejs.org/en/)
> - [Express.js npm](https://www.npmjs.com/package/express)
> - [idb npm](https://www.npmjs.com/package/idb)
> - [CodeMirror Themes](https://www.npmjs.com/package/code-mirror-themes)
> - [webpack-pwa-manifest](https://www.npmjs.com/package/webpack-pwa-manifest)
> - [html-webpack-plugin](https://www.npmjs.com/package/html-webpack-plugin)
> - [babel-loader](https://www.npmjs.com/package/babel-loader)
> - [css-loader](https://www.npmjs.com/package/css-loader)
> - [style-loader](https://www.npmjs.com/package/style-loader)

> [Express.js](https://expressjs.com/)

> [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

> [Workbox](https://developer.chrome.com/docs/workbox/)

> [Webpack](https://webpack.js.org/)

> [Babel](https://babeljs.io/)

> [Heroku](https://www.heroku.com/what)

> [Insomnia](https://docs.insomnia.rest/insomnia/get-started)


## Screenshots

![Screenshot](/client/src/images/19thumbnail.jpg)

This application allows me to not only edit text, exit the application, and return to find my changes preserved, **BUT ALSO** it is able to preserve my changes regardless of whether I am online or offline.

## Contributors

Thank you for checking out my project! If you would like to see more of my work, please take a peek at my [GitHub](https://github.com/anitachengalva/) and [portfolio](http://anitachengalva.github.io/portfolio).

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/anitachengalva)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/anitachengalva)


## License

This project is licensed under the MIT License &nbsp; &nbsp; &nbsp; [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

Please click on the green MIT License Shield above to learn more about what the limitations of this license are.