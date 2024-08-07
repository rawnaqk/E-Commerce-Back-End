# E-Commerce Backend
  
  ![License](https://img.shields.io/badge/license-MIT-blue.svg)
  
  ## Description
   This is a backend implementation for an e-commerce website using Express.js and Sequelize with a PostgreSQL database. It provides an API for managing categories, products, and tags, fulfilling the needs of an e-commerce application.
  
  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  
  ## Installation
  To set up and run the application locally, follow these steps:
  1. Clone the repository: git clone "link of github repository"
  2. Navigate to the applications directory: cd Develop
  3. Install the required dependencies: npm install
  4. Create a '.env' file
  5. Set Up the Database: psql -U postgres; \i db/schema.sql
  6. In a separate bash terminal run: npm run seed
  7. Now run: npm start
  8. By default the server will run on 'http://localhost:3001' if you want to change the port, you can modify the 'config/connection.js' file

  ## Usage
  Once the application is set up and running, you can interact with the API to manage categories, products, and tags. To test the API, you can use tools like Insomnia Core or Postman. You can test the endpoints using the provided request methods (GET, POST, PUT, DELETE) and verify that the responses match the examples provided in the Insomnia example video provided below.
  
  ## License
  This project is licensed under the MIT license.
  
  ## Contributing
  N/A
  
  ## Tests
  [Watch the Video Example](https://drive.google.com/file/d/1AtcyAT8I6x7LB1dJ4VKImsphb9Yuix6x/view?usp=sharing)
  
  ## Questions
  For questions about the project, please contact me via GitHub: [rawnaqk](https://github.com/rawnaqk)  
  or email me at: rawnaq.kabairzad@gmail.com
