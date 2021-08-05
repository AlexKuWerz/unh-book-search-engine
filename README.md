# Book Search Engine

Link to deployed application - https://alexku-book-search.herokuapp.com/

## Description
The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and GraphQL. This application allows you to search by using [Google Books API](https://developers.google.com/books/docs/v1/using#WorkingVolumes). You also can save searched books. To be able to save your books you should create an account and logged in.

## Installation
To be able to use the application you need to install the necessary `npm modules`. You can do this by running the command 

```bash
npm install
```

in the root folder of the project.

You should add configuration data `.env` file with required environment variables to run application localy. File structure:

```
MONGODB_URI='mongodb://localhost/yourDatabaseName'
JWT_SECRET='jsonWebTokenSecret'
JWT_EXPIRATION='2h'
```

## Usage
To run application localy use this command from root folder:

```bash
npm run develop
```

After launch, the local application will be opened in new tab of your browser or you can use the link - http://localhost:3000/.

## Previews

Books search:

![Books search](./res/demo-01.gif)

Books save:

![Books save](./res/demo-02.gif)

View your books:

![View your books](./res/demo-03.gif)

## Credits
Author [Oleksandr Kulyk](https://github.com/AlexKuWerz)
