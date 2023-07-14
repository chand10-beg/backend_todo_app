## Technology Stack 
</br>
Please get familiar with the components of the project in order to be able to contribute.

### components
- CSS: Styling web pages, html files
- Javascript: Primary programing language
- ReactJS: Javascript library for building User Interfaces
- nodejs: Used in the backend
- express: To create the calling API
- Material-UI: UI library for design system

#### External Service Dependencies
- MongoDB Atlas: A cloud database used to store user personal data username, passwords and individuals chats

## Requirements
</br>

- node --version >= 6
- npm --version >= 3


## Local Installation for frontend
</br>
### Steps
- `git clone <repository-url>` where `<repository-url>`is the link to the forked repository
- `cd ToDO_frontend`

Note : If you want to contribute, first fork the original repository and clone the forked repository into your local machine followed by `cd` into the directory


git clone https://github.com/chand10-beg/ToDO_frontend.git


## Local Installation for backend
</br>

### Steps
- `git clone <repository-url>` where `<repository-url>`is the link to the forked repository
- `cd ToDO_frontend`

Note : If you want to contribute, first fork the original repository and clone the forked repository into your local machine followed by `cd` into the directory


git clone https://github.com/chand10-beg/backend_todo_app.git
#### Starting server
cd backend_todo_app

- Install all the dependencies with `npm install`
- Start the server with `npm start`
- Visit your API at [http://localhost:5000](http://localhost:5000.) :tada:

#### Starting frontend


cd ToDO_frontend

- Install all the dependencies with `npm install`
- Start the server with `npm start`
- Visit your app at [http://localhost:3000](http://localhost:3000.) :tada:



#### Config Variables
Define config variables in config.env.

- Create a free mongoDB atlas account at [https://www.mongodb.com](https://www.mongodb.com) and set a new cluster connection url equal to `db_connection_URL`
