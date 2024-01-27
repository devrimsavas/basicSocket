# Program Overview

This program retrieves 20 different memes from the web page: [http://jss.restapi.co.za/memes](http://jss.restapi.co.za/memes) and shows details of the selected meme by pressing the "details" button for logged-in users. Guest users can see only memes' overviews but cannot access details.

## Instructions

1. **Package Installations**: 
   - Program uses different external libraries. Be sure that you have the following packages. To check if you have these libraries, please check the "package.json" file. Here's a list of packages that the program uses:
     - Node express: To install, run `npm install express`
     - Bootstrap: Program uses Bootstrap version 5.2.3. To install this version, run `npm install bootstrap@5.2.3`
     - Ejs Template Engine: Program uses EJS template engine. Be sure that you have installed EJS engine version 3.1.8. Run `npm install ejs@3.1.8`
     - The JavaScript uses jQuery. Run `npm install jquery`
     - For user login requests, the following packages should also be installed:
       - `npm install passport`
       - `npm install passport-local`
       - `npm install express-session`
     - Finally, standard Express packages: `npm install fs`, `path`, `request`.
   
   **"package.json file"** should look like this:
   ![packages](https://github.com/devrimsavas/basicSocket/assets/137702797/9df74743-e8c4-468b-ac6b-2615f5f1ac71)

2. **How the application must run**:
   To run this application, make sure that you have installed the packages mentioned above, and your "config.json" file includes the API link: "apiUrl": [http://jss.restapi.co.za/memes](http://jss.restapi.co.za/memes). The application uses Node Express. To run it, open the terminal in Visual Studio Code or command line and type `npm start`. If you have properly installed the packages, you will see the main page.
