# To Industry!

# Description
A back-end application for an e-commerce site that configures an Express.js API to interact with a MySQL database using Sequelize.

I was provided with starter code for this project, and tasked with adding code to sync Sequelize to the database, creating the models and associations, and completing the routes. The biggest challenge for this project was simply to familiarize myself with the given code in order to determine what was needed to complete the application. 

I used async/await with try/catch for the routes. 

[GitHub repo](https://github.com/rbkeyes/to-industry)

# Table of Contents

- [Installation](#installation)

- [Usage](#usage)

- [Credits](#credits)

- [License](#license)

- [Tests](#tests)

# Installation

To install and run this application, you must have Node.js installed on your computer. Instructions to install can be found [here](https://nodejs.org/en/).

Clone the repository to a local repo. The package-json includes the necessary packages and can be installed by running `npm i` in the terminal command line. 

# Usage

Sign into the MySQL shell and source the schema file using the command `mysql -uroot -p < ./db/schema.sql`. Enter your password when prompted. 

Update the .env file with your sql username and password.

Seed the database using the command `npm run seed`.

Enter `npm start` in the terminal to start the server.

# Credits

