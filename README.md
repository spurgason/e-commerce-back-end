# E-commerce Back-end (ORM)

## Description
This is a mock back-end e-commerce application that incorporates the usage of Object-Relational Mapping (ORM) and RESTful API techniques. This back-end application allows users to get the data of different objects that would commonly be seen in an e-commerce website. Things such as products, the categories that those products would have, and descriptive tags that products would also have. The user can view all or individual products, categories, or tags as well as create, update, or delete them.

## Installation
To install just clone the repository to your local machine. After the repository is cloned `npm init` (initialize) and `npm install` (install) the required packages. Next login to MySQL and run `SOURCE db/schema.sql` and quit MySQl. Back in the command line run `npm run seed` to add the seeds to the database and finally start the server with `npm start`. Don't forget to put in your MySQl credentials into the [connection.js](config/connection.js) file, or create your own .env file to store your credentials. Lastly, you can open Insomnia, or your preferred API client and test each route. 

## Technologies Used
<ul>
  <li>Javascript</li>
  <li>Node.Js</li>
  <li>Express.Js</li>
  <li>NPM Modules
  <ul>
  <li>Sequelize</li>
  <li>MySQL2</li>
  <li>dotenv</li>
  </ul>
  </ul>

## Usage
This application is simply a mock back-end of an e-commerce website. The application only functions through a API client that can GET, POST, PUT, and DELETE data. If the user choses they can manipulate the data as they see fit using an API client. 

## Walkthrough Video
[Watch Walkthough](https://watch.screencastify.com/v/ssOFG0XI8lm7cVgbo1ie) 

## Credits
[Shane Purgason](https://github.com/spurgason)

## Questions
  [Github](https://github.com/spurgason) <br>
  [Email](mailto:shanepurgason.98@gmail.com)