# REST API using Node.js, Express, Sequelize and MySQL + JWT Authentication and Authorization

## Getting Started

1. Clone this repository


2. Install the npm packages

   ```bash
   npm install
   ```

   Also install `nodemon` globally, if you don't have it yet.

   ```bash
   npm install -g nodemon
   ```

3. Open xampp start Apache and MySQL and create a database in your localhost

4. Congfigure environment settings

   Create a file with the following name and location `.env` and copy the contents from `.env.example` into it. Replace the values with your specific configuration. Don't worry, this file is in the `.gitignore` so it won't get pushed to github.

   ```javasscript
    NODE_ENV=development
    PORT=8081 # Recommended to set port as 8081 because 8080 will redirected to apache dashboard

    # Database
    DB_HOST=host -for ex. localhost
    DB_USER=username -for ex. root
    DB_PASS=password -for ex.  (blank)
    DB_NAME=db-name -for ex. node_sequalize_db
   ```

5. Running the app locally

   Run this command, which is located in npm script in `package.json` file.

   ```bash
   npm run dev


   ```

## Author
   - [@milanmsp7](https://www.github.com/milanmsp7)