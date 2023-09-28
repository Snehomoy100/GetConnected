# GetConnected

Welcome to GetConnected, your passport to a vibrant global social experience. Connect with people worldwide and explore diverse cultures and ideas.

## Features

- **Global Reach**: Connect with people from around the world.
- **User-Friendly Interface**: Navigate effortlessly.
- **Secure Login and Registration**: Your privacy is our priority.
- **Real-Time Notifications**: Stay updated.
- **Private Messaging**: Connect privately.
- **Post Creation**: Share your thoughts effortlessly.
- **Comments**: Engage in discussions.
- **Profile Customization**: Make your profile unique.
- **Followers and Following**: Build your network.
- **Powerful Search**: Find friends and interests.

## Technologies
|   Front End |  Back End   |
| ----------- | ------------|
| React       | Node        |
| TypeScript  | MongoDB     |
| Redux       | Mongoose    |
| Redux-Saga  | SocketIO    |
| React Router| Express JS  |
| TailwindCSS | Passport JS |
| PostCSS     | Cloudinary  |
| Axios       |             |

## Installation
To install both ends (client/server). 
```
$ npm run init-project
```

Or to install them individually
```
$ cd client // or cd server
$ npm install
```

## Run locally
Before running the project, make sure to have the following done:
* Download and install [MongoDB](https://www.mongodb.com/)

Create ```.env-dev``` or ```.end-prod``` env variables in  ```/server```  and set the following:
```
MONGODB_URI=<mongodb uri | default local: mongodb://localhost:27017 >
DB_NAME=<your database name>
PORT=<port eg: 9000>
CLIENT_URL=<your frontend url, default: http://localhost:3000>
SESSION_SECRET=<any secret key>
SESSION_NAME=<any name you want>
CLOUDINARY_NAME=<you cloudinary name>
CLOUDINARY_API_KEY=<you cloudinary api key>
CLOUDINARY_API_SECRET=<you cloudinary secret>
GOOGLE_CLIENT_ID=<you app client id>
GOOGLE_CLIENT_SECRET=<you app client secret>
FACEBOOK_CLIENT_ID=<you app client id>
FACEBOOK_CLIENT_SECRET=<you app client secret>
```

And create ```.env``` variables in  ```/client```  and set the following:
```
REACT_APP_GETCONNECTED_URL=<you url backend | default: http//localhost:9000>
REACT_APP_GETCONNECTED_API_VERSION=<api version | default: v1>
```

After doing the steps above, you have to run your ```Mongo Server``` and finally you can now run both ends simultaneously by running: 

```
$ npm start
```

Or you can run them individually

```
$ npm run start-client // frontend
$ npm run start-server // backend

// Or you can change to individual directory then run 
$ cd client // or cd server
$ npm start
```

## Message from creator
Build with ♥️ in 🇮🇳 by Snehomoy Maitra