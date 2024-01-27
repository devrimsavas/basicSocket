#Program Overview

This program retrieves 20 different memes from the web page: [http://jss.restapi.co.za/memes](http://jss.restapi.co.za/memes) and show details of selected meme by pressing details button for logged users. Guest users can see only memes' overview but not access to details.

**Instructions**

1. **Package Installations** : Program uses different external libraries: Be sure that you have following packages: In order to check if you have these libraries, please check "package.json" file. Here the list of packages that program uses
 Node express: to install, " **npm install express**"
 Bootstrap: Program uses bootstrap version 5.2.3, for install this version: " **npm install bootstrap@5.2.3**"
 Ejs Template Engine: Program uses EJS template engine be sure that you have installed EJS engine version 3.1.8 " **npm install ejs@3.1.8"**
The java scripts use jQuery: " **npm install jquery**"
 for user login request the following packages should also be installed:
 - npm install passport
 -npm install passport-local
 -npm install express-session
 and finally standard express packages
 npm install fs, path, request.
**"package.json file"** should be seen:
![packages](https://github.com/devrimsavas/basicSocket/assets/137702797/9df74743-e8c4-468b-ac6b-2615f5f1ac71)


2. **How the application must run**
to run this application be sure that you have installed the packages above and " **config.json"** file includes API link : " **apiUrl":** [**http://jss.restapi.co.za/memes**](http://jss.restapi.co.za/memes). The application uses node express, in order to run open terminal in Visual Studio Code application or command line and type "npm start". If you have properly installed the packages you would see the main page.

