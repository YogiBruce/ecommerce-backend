# EMPLOYEE TRACKER
![Github licence](https://img.shields.io/badge/License-MIT-blue.svg)

## Description
This command line application allows a user to run an ecommerce backend API for an online retail website. User will be able to create, read, update, and delete from products, product categories, and product tag designations. This backend application is not deployed to a browser and so an API interface app will be needed to run commands. This app demonstrates CRUD and back-end api routing using ORM principles to dynamically manipulate and display info from a MySQL database.

#
## Table of Contents
- [Installation](#installation)
- [Github Repository](#github-repo)
- [Screenshot](#screenshot)
- [Usage](#usage)
- [Demonstration Videos](#demo-video)
- [Tests](#tests)
- [License](#license)
- [Questions](#questions)

#
## Installation
<a id="installation"></a>
User will need to have Node.js and mySQL installed to run application. Clone YogiBruce's "ecommerce-backend" repository from GitHub to local drive. From the command line; run "mysql -u root -p" then "source db/schema.sql". The user will then need to run npm run seed to preload seed to database.  Once dependencies are installed and mySQL has been started, the user can initiate application by running "npm start" and then using an API interface such as Insomia to run CRUD requests.

### GitHub Repository
<a id="github-repo"></a>
You may clone this repo to begin using application: [GitHub repo](https://github.com/YogiBruce/ecommerce-backend)

<a id="Screenshot"></a>
<img src="assets\API-category-screenshot.jpg" width="500px"/>

#
## Usage
<a id="usage"></a>
User will need to run "npm run seed" and "npm start" from the command line to begin application. The user will then need to navigate to an API interfacing application such as Insomnia to run GET, POST, PUT, and DELETE requests through the ecommerce backend application.

### Demonstration Videos
<a id="demo-video"></a>

GET routes to return all categories, all products, and all tags.
<img src="" width="500px"/>

GET routes to return a single category, a single product, and a single tag.
<img src="" width="500px"/>

POST, PUT, DELETE routes for categories.
<img src="" width="500px"/>

Follow this link to view walk-through video of application: [Google Drive](https://drive.google.com/file/d/1IUN5gQMWFec1_Y1tWvkCjNGf6nmx0L9u/view?usp=share_link)

#
## Tests
<a id="tests"></a>
There are no tests for this application. Incorrect data-type or missing attributes will throw errors, invalid routes will return not found.


#
## License
<a id="license"></a>

#### MIT License [vist link](https://choosealicense.com/licenses/mit/)
Copyright 2022 - Robert B Arnold Jr

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


#
## Questions?
<a id="questions"></a>
For any questions regarding this application or any other project by YogiBruce:

### Email: [Gmail](da.bruce.jr@gmail.com)

### Gihub Profile: [YogiBruce](https://github.com/YogiBruce) 