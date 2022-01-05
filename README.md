<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![GitHub][github-shield]][github-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">E-commerce Back-end</h3>

  <p align="center">
    Keeping track of backend online shopping
    <br />
    <a href="https://github.com/spurgason/e-commerce-back-end"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/spurgason/e-commerce-back-end">View Demo</a>
    ·
    <a href="https://github.com/spurgason/e-commerce-back-end/issues">Report Bug</a>
    ·
    <a href="https://github.com/spurgason/e-commerce-back-end/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![E-commerce Back-end][product-screenshot]](https://afternoon-crag-71195.herokuapp.com/)

This is a mock back-end e-commerce application that incorporates the usage of Object-Relational Mapping (ORM) and RESTful API techniques. This back-end application allows users to get the data of different objects that would commonly be seen in an e-commerce website. Things such as products, the categories that those products would have, and descriptive tags that products would also have. The user can view all or individual products, categories, or tags as well as create, update, or delete them.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/)
* [Sequelize](https://sequelize.org/)
* [MySQL2](https://www.npmjs.com/package/mysql2)




<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Once the repo has been cloned to your local machine you will need to put your MySQL credentials into the [connection.js](config/connection.js) file, or create your own .env file.

### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/spurgason/e-commerce-back-end.git
   ``` 
2. Login to MySQL and run 
   ```sh
   SOURCE db/schema.sql
   ```
3. Seed the database
   ```sh
   npm run seed
   ```
3. Start the the application on [localhost:3001](http://localhost:3001/)
   ```sh
   npm run start
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This application is simply a mock back-end of an e-commerce website. The application only functions through a API client that can GET, POST, PUT, and DELETE data. If the user chooses they can manipulate the data as they see fit using an API client such as Insomnia or Postman.

[Watch Walkthrough Video](https://watch.screencastify.com/v/ssOFG0XI8lm7cVgbo1ie) 

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Email: [spurgason.98@gmail.com](spurgason.98@gmail.com)

Project Link: [https://github.com/spurgason/e-commerce-back-end](https://github.com/spurgason/e-commerce-back-end)

<p align="right">(<a href="#top">back to top</a>)</p>

 
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/spurgason/e-commerce-back-end.svg?style=for-the-badge
[contributors-url]: https://github.com/spurgason/e-commerce-back-end/graphs/contributors

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/shane-purgason-0b3a96199

[github-shield]: https://img.shields.io/badge/-GitHub-black.svg?style=for-the-badge&logo=github&colorB=555
[github-url]: https://github.com/spurgason

[product-screenshot]: assets/e-commerce-back-end-example.PNG
