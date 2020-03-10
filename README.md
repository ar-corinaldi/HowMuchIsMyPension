# HowMuchIsMyPension

HowMuchIsMyPension is a project where you can register your pension plan fees and get all the details in the quotation process like the pension you are getting today and number of months left to get the expected amount. This is only useful if you are in Colombia.

<img width="1440" alt="Captura de pantalla 2020-03-01 a la(s) 6 46 30 p  m" src="https://user-images.githubusercontent.com/26877363/75636461-0b1c4400-5bed-11ea-8fc3-e81d1e76cdb2.png">

<img width="1440" alt="Captura de pantalla 2020-03-01 a la(s) 6 46 00 p  m" src="https://user-images.githubusercontent.com/26877363/75636464-0fe0f800-5bed-11ea-9e8a-7c88f0c16ded.png">

<h2>Demo</h2>

<a>https://youtu.be/ZzcRwIRHeXA</a>


<h2> Technologies </h2>
<ul>
  <li>JavaScript</li>
  <li>MongoDB</li>
  <li>Express</li>
  <li>NodeJs</li>
  <li>PassportJS</li>
  <li>HTML5</li>
  <li>CSS</li>
  </ul>
<br>

## Requirements

NodeJs
Previous installation of Nodejs is required. If you don't have it, go to <a>https://nodejs.org/es/download/</a>.

MongoDb
Expects a Mongo Server to be running on Mongo Atlas DataBase, and it uses a database called "PensionDB" with the collections "ipcs", "usuarios", "cotizaciones".
If running locally, install MongoDB. To install it just go to: <a href="https://www.mongodb.com/download-center/community">MongoDB Community Server</a>

Once installed, on the project's root run npm install mongodb --save to install the MongoDB driver as well as its dependencies.
<br>

## Installation

1. Get in the folder of the project
2. Install dependencies with the package manager [yarn](https://yarnpkg.com/)
3. Deploy the project

```bash
cd HowMuchIsMyPension
yarn install
yarn start
```
Server runs on http://localhost:8080
<h2>IMPORTANT!</h2>

In order to run locally you must create a .env file containing any environment variables;  DB_USERNAME= <database_Username>,
DB_PASSWORD=<databas_password>, DB_NAME=<naemOfYourDatabase> , SECRET=<secretSessionKey>. This is going to be required by the dotenv module.

<br>
<h2> Link </h2>

<a>https://how-much-is-my-pension.herokuapp.com </a>

<br>

## Authors

[Allan Roy Corinaldi Castaño]<a>(https://github.com/ar-corinaldi)</a>

[Daniella Arteaga Mendoza]<a>(https://github.com/dartm05)</a>

<br>

## License
[MIT](https://choosealicense.com/licenses/mit/)
