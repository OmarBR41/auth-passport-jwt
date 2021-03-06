# Auth App - Server

This is the backend of the authentication app.

Developed with Node.js. The backend has an Express.js web server running in port 5000. It has a MongoDB connection established with Mongoose, with one model schema for the User. Passport.js handles the authentication with a JWT strategy, also added a basic validation.

## Environmental Variables

You need to create a .env file in the server/ directory with the following keys:

- MONGO_URI="mongodb://localhost/auth_db"
- SESSION_SECRET=secret
- SECRET_OR_KEY="secret"

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode using 'nodemon'.\
The server will reload if you make edits.\
You will also see any lint errors in the console.

### `npm start`

Launches the server in production mode.\
