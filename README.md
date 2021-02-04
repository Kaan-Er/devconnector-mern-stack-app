# DevConnector

## Social network for developers
It is a small social network app that includes authentication, profiles and forum posts.


## Quick Start 🚀

Add a default.json file in config folder with the following

    {
      "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
      "jwtSecret": "secret",
      "githubToken": "<yoursecrectaccesstoken>"
    }

### Install server dependencies

    npm install

### Install client dependencies

    cd client
	npm install

### Run both Express & React from root

    npm run dev

### Build for production

    cd client
	npm run build

### Test production before deploy

After running a build in the client  👆, cd into the root of the project.  
And run...

Linux/Unix

    NODE_ENV=production node server.js

Windows Cmd Prompt or Powershell

    $env:NODE_ENV="production"
	node server.js
Check in browser on [http://localhost:5000/](http://localhost:5000/)
