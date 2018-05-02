# task-manager
Node.js, MongoDB + Angular 5.2 - app "Task Manager"
[Demo](https://task-manager-by-sentino.herokuapp.com/)

This application was created solely for informational purposes and is not a reliable example of how to build an ideal application. You can use separate elements, but it is not recommended to use the entire application in full. For security, it is recommended that you change all encryption keys on the server before use, in order not to compromise the information from the database

## Config
#### Server:

**server/index.js**:
 
 mongoose.connect(`'mongodb://localhost:27017/taskManager'`, {}) -
URL of the MongoDB database


#### Client:

**client/src/environments/environment.ts**: 

ws_url: `'http://localhost:3000/'` - URL of the server websocket

api_url: `'http://localhost:3000/'` - URL of the server api


**client/src/environments/environment.prod.ts**: 

ws_url: `'***'` - URL of the server websocket product

api_url: `'***'` - URL of the server api product