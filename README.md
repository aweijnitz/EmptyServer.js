# EmptyServer.js
An Express4 server scaffold with focus on the server life-cycle.

Features

- Application life-cycle management
    * Pre-start setup hook
    * Shutdown hook on 'SIGINT' and 'SIGTERM' for pre-exit cleanup or data saving.
- Logging using [log4js](https://github.com/nomiddlename/log4js-node)
    * Config includes both rotating file and console logging
- Application config injection
    * Simple pattern for injecting config and logger info in modules (see `routes/upload.js` for example)
- Built in form parsing with Formidable
    * Example includes file upload form
- Example test cases 
    * Using [Mocha](http://visionmedia.github.io/mocha/) and [Should](https://github.com/visionmedia/should.js/)

## Install
First clone/save this repo

    cd EmptyServer
    mkdir logs
    mkdir uploadDir
	npm install
## Run
	npm start
## Run tests
	npm test
	
<img src="http://mildly-interesting.info/images/startShutown.png" alt="Server startup" style="width:640px;">	
	