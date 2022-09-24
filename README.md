# E-Commerce Backend Project

  ## Table of contents
  1. [Submission](#submission)
  2. [Description](#description)
  3. [Usage](#usage)
  4. [Visuals](#visuals)

  ## Submission
  [Link to Screencastify Video](https://watch.screencastify.com/v/nKCrxETobELRk5BdLWy7)


  ## Description
  This is a a demonstration of a backend system for an ecommerce website. Through Insomnia, users can view all, view by ID, create new, update, and delete different Categories, Products, and Tags.
 
  ## Usage
  Clone the project, navigate to it and type into your terminal "npm i" to install all the of the node modules listed in the "package.json". Then, run the command "mysql -u root" to log into the mysql terminal, then run the command "SOURCE db/schema.sql" to set the database, then in the mysql terminal enter "exit" to return to the main terminal. From there run npm run seed" to populate the database. Then, to host the databse, run in the terminal "nodemon server.js" or just "node server.js". From there, you can open up Insomnia. In the main directory is a file called "Ecommerce-Backend-For-Insomnia.json". Users can import this file into Insomnia to quickly access the different requests to interact with the database.

  ## Visuals

 ![Alt text](/Assets/ecommerce_insomnia_screenshot.png "Image of the CMS in git bash")