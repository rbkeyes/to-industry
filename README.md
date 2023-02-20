# To Industry!

![repo License](https://img.shields.io/github/license/rbkeyes/team-profile-generator?color=green)
![GitHub language count](https://img.shields.io/github/languages/count/rbkeyes/team-profile-generator?color=purple)
![GitHub top language](https://img.shields.io/github/languages/top/rbkeyes/team-profile-generator)


## Description
A back-end application for an e-commerce site that configures an Express.js API to interact with a MySQL database using Sequelize.

I was provided with starter code for this project, and tasked with adding code to sync Sequelize to the database, creating the models and associations, and completing the routes. The biggest challenge for this project was to familiarize myself with the given code in order to determine what was needed to complete the application. 

I used async/await with try/catch for the routes. 

[GitHub repo](https://github.com/rbkeyes/to-industry)

This application is not deployed.


## Table of Contents

- [Installation](#installation)

- [Usage](#usage)

- [Demo Videos)(#demo)

- [Credits](#credits)

- [License](#license)

- [Tests](#tests)


## Installation

To install and run this application, you must have Node.js installed on your computer. Instructions to install can be found [here](https://nodejs.org/en/).

Clone the repository to a local repo. The package-json includes the necessary packages and can be installed by running `npm i` in the terminal command line. 

To view the API data, you will need to install [Insomnia](https://insomnia.rest/download) or a similar API development platform.


## Usage

Sign into the MySQL shell and source the schema file using the command `mysql -uroot -p < ./db/schema.sql`. Enter your password when prompted. 

Update the .env file with your sql username and password.

Seed the database using the command `npm run seed`.

Enter `npm start` in the terminal to start the server.

You can view the API data by running the routes in Insomnia, or your API development platform of choice.


## Demo

1. Terminal commands to source and seed database, start application:

https://user-images.githubusercontent.com/114431225/220197619-755cb0dd-024d-48f7-a7af-f6e0c6c0e3db.mp4


2. Categories routes:

https://user-images.githubusercontent.com/114431225/220197720-a403d56d-e4d3-49fb-beb8-be667217d69f.mp4


3. Products routes:

https://user-images.githubusercontent.com/114431225/220197750-d4ef7b7f-4d95-41da-acf2-c529b3e70c94.mp4


4. Tags routes:


https://user-images.githubusercontent.com/114431225/220197801-90df0288-2ea1-4606-bf68-5730d4269939.mp4



## Credits

Starter code provided by U.C. Berkeley coding bootcamp. 

Coursework for the bootcamp was used as reference material in completing this project.


## License

[MIT license](./LICENSE)


## Tests

There are no tests at this time.


## Contact

Still have questions? Find me on [GitHub](https://github.com/rbkeyes).

Or, you can [email me](mailto:rbkeyes@gmail.com).

