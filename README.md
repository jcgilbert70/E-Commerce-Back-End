
  # E-Commerce-Back-End
  

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
 
  ## Description
  
  A back end application that will read, create, update and delete categories, products, and tags in an E-Commerce database. This Application uses MySQL, Sequelize, and Express.js. 

  ## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

  ## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
 
  ## Table of Contents
  - [Installatoin](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Questions](#questions)
  
 
  ## Installation
  
  You will need to use node.js, MySQL as well as installing all dependencies using "npm install" in your terminal within the applications directory. You will also need Insomnia in order to perform the CRUD operations with the database. 
  
  ## Usage
  
  You will need to have everything istalled as mentioned in "Installation". The while within the applications directory you will need to log into MySQL. from there you will need to enter command "SOURCE db/schema.sql;" to create the database. Next you will exit MySQL with "/exit" and then enter command "npm run seed". This will seed the database with provided data. To be able to use the database you will then need to enter command "npm start" to initialize the server. Now you can open up Insomnia and begin viewing or manipulating the database. You can view a demonstration in the below Video Demo within the "Links" section
 
 
  ## Contributing
  

  If you would like to contribute to this repository, follow these instructions: 
  

  This repository is open to the public to access, please feel free to comment.
  
  ## Screenshots

```MySQL create Database```

 <img src="./assets/img/MySQL.png" width="300">

```Seed the Database```

 <img src="./assets/img/Seeds.png" width="300">

```Initialize Server```

 <img src="./assets/img/Server.png" width="300">

```Categories in Insomnia```

 <img src="./assets/img/Categories.png" width="300">

```Products in Insomnia```

 <img src="./assets/img/Products.png" width="300">

```Tags in Insomnia```

 <img src="./assets/img/Tags.png" width="300">

  ## Links

  Video Demo: 
  https://app.castify.com/watch/38bc4006-cf4a-4fbc-a6e3-369a80b085cd

  Repository: 
  https://github.com/jcgilbert70/E-Commerce-Back-End.git


  ## Questions
  Any questions about this project please contact the creator jcgilbert70 at:
  jcgilbert70@gmail.com
  

  Check out other repositories by this creator at: https://github.com/jcgilbert70
  

  ## License: MIT
  
 
  MIT License Link: https://opensource.org/licenses/MIT

  
