# Indian Temples web app
A web app where an user can see famous temples in india . add new temples delete and review them.

User Permissions :

## A user can

1.register himself on the app 
2.view temples 
3.add reviews
 
## An Owner of a temple can

1.view and edit his temple
2.Delete temples made by him.
3.add new images

View live App
Hosted at https://desolate-savannah-29894.herokuapp.com/

## Tech Stack Used

* [MongoDB](https://docs.mongodb.com/) - Document database - to store data as JSON 
* [Express.js](https://devdocs.io/express/) - Back-end web application framework running on top of Node.js
* [Node.js](https://nodejs.org/en/docs/) - JavaScript runtime environment 

### Middleware

* [Mongoose](https://mongoosejs.com/docs/guide.html) - ODM for MongoDB


## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/SinghAman1/Indian-temples.git
cd yelpcamp
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).

To get google maps working check [this](https://github.com/nax3t/google-maps-api) out.
