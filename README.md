# Indian Temples web app
A web app where an user can see famous temples in india . add new temples delete and review them.

User Permissions :

A user can
register himself on the app 
view temples 
add reviews
 
An Owner of a temple can

view and edit his temple
Delete temples made by him.
add new images

View live App
Hosted at https://lib-manage.herokuapp.com/

Tech Stack Used

MongoDB - Document database - to store data as JSON
Express.js - Back-end web application framework running on top of Node.js
Node.js - JavaScript runtime environment 

Middleware
Mongoose - ODM for MongoDB 


## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/himanshup/yelpcamp.git
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