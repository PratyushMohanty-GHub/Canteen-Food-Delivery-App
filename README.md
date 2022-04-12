# MERN Stack Boilerplate

## Description
- I present to you a dynamic food ordering portal
- Users have the option to search and order various food items. At the same time, various vendors have the ability to list food items.
- Multiple Users can Rate Food items listed by various venders, buy addons and food items via their wallet money 
  and track the status of their order
- Multiple venders can list their food items and addons and can accept user orders. They can move and monitor the status of the order
- Venders and Users can view and edit their registration details. Venders can view order statistics.

## Code details
- React JS for Frontend
- Backend Framework using Express JS implementing REST API.
- Node JS for Backend
- MongoDB for Database
- Dockerized 

## Installations

### Node

* For Linux:
```
curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt-get install -y nodejs
```

* For Mac:
```
brew install node
```

### MongoDB

Install the community edition [here](https://docs.mongodb.com/manual/installation/#mongodb-community-edition-installation-tutorials).


### React

```
npm install -g create-react-app
```

* To create a new React app:
```
create-react-app name_of_app
```

* To run the app, cd into the directory and do:
```
npm start
```

## Running the boilerplate

* Run Mongo daemon:
```
sudo mongod
```
Mongo will be running on port 27017.


* Run Express Backend:
```
cd backend/
npm install
npm start
```

* Run React Frontend:
```
cd frontend
npm install/
npm start
```

Navigate to [http://localhost:3000/](http://localhost:3000/) in your browser.

