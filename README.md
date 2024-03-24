# Local Library <img align=right width=40 src="https://www.svgrepo.com/show/475352/book.svg" alt=""/>

A comprehensive example of building a full-stack JavaScript application using Node.js, Express, and MongoDB.

The application provides a platform for librarians to manage books, book instances, authors, genres, and user accounts.

It covers various aspects of web development, including data modeling, routing, authentication, and deployment.

## Features

- Browse and search for books, authors, genres, and book instances
- Create, update, and delete books, authors, genres, and book instances
- Manage user accounts and authentication
- Borrow and return book instances
- View the list of borrowed books for each user

## Tech Stack

<div align=center>

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) &nbsp;&nbsp; ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) &nbsp;&nbsp; ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) &nbsp;&nbsp; ![Mongoose](https://img.shields.io/badge/Mongoose-880000.svg?style=for-the-badge&logo=Mongoose&logoColor=white) &nbsp;&nbsp; ![PUG](https://img.shields.io/badge/Pug-A86454.svg?style=for-the-badge&logo=Pug&logoColor=white) &nbsp;&nbsp; ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3.svg?style=for-the-badge&logo=Bootstrap&logoColor=white)

</div>

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/0xabdulkhalid/local-library-using-express.git
   ```

2. Install dependencies:

   ```
   cd local-library-using-express
   npm install
   ```

3. Set up the MongoDB connection by creating a `.env` file with the following content:

   ```
   MONGO_URI=your-mongodb-connection-string
   ```

4. Start the application:

   ```
   npm start
   ```

5. Open your web browser and navigate to `http://localhost:3000` to access the Local Library application.

## Deployment

- The Local Library using Express application is deployed on Glitch, a platform for hosting and deploying web applications.

- Please note that since the application is hosted on the free tier of Glitch, the initial load time may be slower due to the server's cold start. (Approx 5 mins)

- You can access the deployed application [here](https://local-library-using-express.glitch.me/)

## License

This project is licensed under the [MIT License](LICENSE).
