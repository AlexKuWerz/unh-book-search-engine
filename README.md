# Book Search Engine

Link to deployed application - https://alexku-book-search.herokuapp.com/

## Description


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
