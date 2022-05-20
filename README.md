# <h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End 👋</h1>

<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>


## Description
My goal is to build the back end for an e-commerce site by taking a working Express.js API and configuring it to use `Sequeliz`e to interact with a `MySQL` database. Since this project will not be deployed, please check out the full walkthrough video posted below to view its functionality.



## Table of Contents

- [Installation](#getting-started)
- [Usage](#usage)
- [Deployed Site](#deployed-site)
- [Tech Used](#tech-used)
- [Contact](#contact)
- [License](#license)
- [Contributing](#contributing)


```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Demo
🎥 Full video -> https://watch.screencastify.com/v/WFlq1UPr2zJiCSBo8x3c

![cats](https://user-images.githubusercontent.com/87335354/140693196-34f2ef38-c2ee-43e4-b38a-152c9978a41f.gif)

![product (1)](https://user-images.githubusercontent.com/87335354/140693083-7fcf0eb3-6f4e-4983-a223-9c536de63913.gif)

![tags](https://user-images.githubusercontent.com/87335354/140693093-9e93a9e2-0696-48b1-8648-67e675d05e20.gif)


## Getting Started
Clone [the starter code](https://github.com/coding-boot-camp/fantastic-umbrella).

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`


## Usage
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`


## Contact

[GitHub](https://github.com/pamelac21)

[email](mailto:pamelac021@gmail.com)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

















