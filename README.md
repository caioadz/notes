# Notes

The purpose of this project is to show a simple way to build your API's controllers.
This was inspired by frameworks like ASP.NET MVC or Web API, where you can define your routes and verbs with Annotations on your Actions.

- **server.js**: Entry point of Node server
- **boot.js**: Iterates throught all files inside controllers folder, importing its content and configuring Express routes
- **db.js**: Some predefined data that will be handled by the controllers
- **note.js**: The controller itself. Here we define actions, its routes and allowed verbs.

The routes will be configured in the following pattern: _//example.com/controller_name/action_route_
