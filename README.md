
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# Budget Tracker - IndexDB app 

## Table of Contents
1. [Description](#descrip) 
2. [Installation](#install)
3. [Usage](#usage)
4. [License](#lic)
5. [Contributing](#contri)
6. [Tests](#test)
7. [Questions](#quest)

---------------------------------------
## 1. Description <a id="descrip"> </a>
Project implements an IndexDB app which allows for offline operation.  IndexDB uses an object data base located in the browser (client side).  The creation and all CRUD operations are invoked through JavaScript and found in the db.js file in Public folder on the client side. Once the application is back online the IndexDB bulk transfers all content to the MongoDB in the server and purges its documents.

----------------------------------------------

## 2. Installation <a id="install"></a>
Installation Instructions: 

1) Clone from repo noted below.  2) Run npm i in terminal found where the packag.json file is 3) Run node server.js to instantiate MongoDB database and IndexDB. 4) Open localhost port 3333 and enter some budget data.  4) Open Dev Tools and find Network tab and take server offline. 5) Add more budget data in browser (this data is loading into IndexDB - see Applications tab in Dev tools and.  6) Bring Network back online and examine the server data base to see all documents added during the offline operation have been uploaded to server, and then purged from the client side IndexDB.

Files used in API found : https://github.com/gmcmurray/PWA-BudgetTracker 

API deployed here on Heroku: https://warm-waters-18979.herokuapp.com/

-------------------------------------------------

## 3. Usage <a id="usage"></a>
The API is target to be used:
IndexDB are used to enable offline operation.  This is helpful when there is a loss in connection by providing continuity for the application using the local IndexDB.

-----------------------------------------------------

## 4. License <a id="lic"></a>

License covering API:
MIT License
    Copyright (c) <2021> <George McMurray>
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

----------------------------------------------

## 5. Contributing <a id="contri"></a>
George McMurray

-------------------------------------------------

## 6. Tests <a id="test"></a>
The following tests were conducted on the API:
Browser Inspection Dev Tools, Insomnia and Robo3T tools were used to debug and validated applicaiton.

----------------------------------------------------------------

## 7.  Questions <a id="quest"></a>
For any questions you can email me at:
gmcmurray1493@gmail.com

My github username is gmcmurray

---------------------------------
