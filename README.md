
# Currency Convertor api

 A simple app that performs basic user authentication methods

## Features
- User can Register an account.
- Users can Login to the application
- Users can see their profiles.

## Tools
Tools used for development of this API are;
- Database: [PostgreSQL](https://www.postgresql.org)
- Framework: [ExpressJS](http://expressjs.com/)
- Code Editor/IDE: [VSCode](https://code.visualstudio.com)
- Programming language: [JavaScript(ES6)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/)
- API Testing environment: [Postman](https://www.getpostman.com)


## Getting Started
1. After cloning the repository from [here](https://github.com/shemaeric/NodeApp), install requirements by running this command in the root of the repo folder
```sh
    $ npm install
```

2. Create a PostgreSQL database and take note of the database configurations.

3. Make a copy of `.env.sample` and rename it to `.env`. Edit the file replacing the respective configuration values.

4. Run the following commands in the projects root to set up migrations and to seed the database 
```sh 
    $ npm run migrate
    $ npm run seed
 ```
5. Run the following command to start the API server:
```sh
    $ npm start
```


### Key Contributors
- [Eric Shema](https://github.com/shemaeric)