# textEditorPWA

## Description
This project is a Progessive Web Application Text Editor that is fully operational in the browser with capability to download as a Chrome Web Application to your local machine.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Overview](#overview)
- [Links](#links)
- [Contact](#contact)

## Installation
As a user the application can be accessed via the deployed link provided below. 
To access the application via source files an npm install will be necessary. The package.json file contains the following dependencies necessary for the application to function properly:
{"name": "JATE", "version": "1.0.0", "engines": {"node": "20.x"}, "scripts": {"dev": "webpack-dev-server", "build": "webpack --mode production", "start": "webpack --watch"}, "author": "2U","license": "UNLICENSED","dependencies": {"code-mirror-themes": "^1.0.0","idb": "^6.1.2","@babel/core": "^7.15.0", "@babel/plugin-transform-runtime": "^7.15.0", "@babel/plugin-proposal-object-rest-spread": "^7.20.7", "@babel/preset-env": "^7.15.0", "@babel/runtime": "^7.15.3", "babel-loader": "^8.2.2","css-loader": "^6.2.0", "html-webpack-plugin": "^5.3.2","http-server": "^0.11.1","style-loader": "^3.2.1", "webpack": "^5.51.1", "webpack-cli": "^4.8.0", "webpack-dev-server": "^4.0.0", "webpack-pwa-manifest": "^4.3.0", "workbox-webpack-plugin": "^6.2.4"}}

## Usage
### User Story
```md
AS A student or business professional
I WANT a simple text editor application that can be downloaded as an application on my computer
SO THAT I have available to me a place to store temporary text/data as I toggle between various applications
```
## License
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Contributing
At the initiation of this project a file structure containing starter code was provided. 

## Application Overview
The final product of the application has been deployed to Heroku. The application is fully functional within the web browser and additionally contains offline capabilities as a locally installed application.  

Initially upon opening the application there will be default text resembling the project logo. This text can be easily removed from the application as new text is entered. If the Install button is clicked a prompt should be provided to the user to confirm if the application should be downloaded. Once downloaded to the system and opened, the applicatiom will open in its own window. 

As the text editor is used the data typed into the text editor by the user is stored under the Indexed DB in a field named 'JATE.' A cache is being stored in the Cache Storage application element.

## Links
Deployed Heroku App: [anotherwebtexteditor](https://anotherwebtexteditor-8964003501f4.herokuapp.com/)
Repo: [textEditorPWA](https://github.com/rickdeakins/textEditorPWA)

## Contact
GitHub: [rickdeakins](https://github.com/rickdeakins)
Email: [rickdeakinsjr@gmail.com](mailto:rickdeakinsjr@gmail.com)
