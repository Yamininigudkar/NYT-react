# NYT -React Search App

## Overview
This is a React-based rendition of the New York Times Article Search application.It makes call to nytimes API to get search results.User can search for an articles by topic , start date and end date.Application also allows user to save articles and remove articles from saved list.
Mongo db is used for saving articles.

Click on link below to check out the web app
https://guarded-mesa-27877.herokuapp.com/

### Key Dependencies

`react - used for building user interface

`react-dom - This package serves as the entry point of the DOM-related rendering paths. 

`react-scripts - This package includes scripts and configuration used by Create React App.

`react-router-dom - DOM bindings for React Router.

`mongoose`: be in charge of database of `NYT react`

`express`: builds server-side routes and functions

`body-parser: Parse incoming request bodies in a middleware before your handlers, available under the req.body property.

### Run locally on your system
- git clone this repository on your system  https://github.com/Yamininigudkar/NYT-react.git
- on seperate shell window run mongod
- cd into your folder
- run yarn install inside your root directory
- cd into client and run yarn yarn install again
- cd back and run yarn start. This should open the app in your browser


### Moving forward
- Improve user interface
- Add user login 
- * Use React routing and [socket.io](http://socket.io) to create a notification or a component that triggers whenever a user saves an article. Your message should include the title of the saved article.
  * Say you have multiple browsers open, each one visiting your site. If you save an article in one browser, then all of your browsers should notify you that a new article was saved.
  * [Socket.io NPM package](https://www.npmjs.com/package/socket.io)