# {FlashStash}
Never forget anything! Organize your much needed study materials into virtual flashcards and drop your paper counterparts behind.  
 

# Technologies Used
* Node/Express
 	* modules:
     * Passport / Bcrypt - Authentication and password hashing
* React
	* Key modules:
	 * Axios
	 * React-router-dom
	* CSS Framework: React-Bootstrap
* MongoDB with Mongoose

# Approach Taken
We took some time in the first day to split up the app development into sprints which is broken down into frontend and backend development

##Sprint1 - Setup 
Brainstorm, share and narrow down choices
Create trello board and label the sprints with their distintive colors
Developed wireframes of the application
![](/client/public/img/LayoutStructure.png)
Created Component structure based on wireframe
![](/client/public/img/ComponentWireFrame.png)
Made a basic database model Users that contains user data and Deck/card data

##Sprint2 - Backend 
Basic frontend pages with directions on where the data should be rendered
Post routes to create both a new deck of cards and individual cards
Delete routes so a user can delete a unused card
Basic error handling for input forms to prevent odd data entries

##Sprint3 - Frontend 
Revisited components and revised some routes for better User flow
Created basic styles all the pages
Fix bugs that are 

# Issues/Unresolve problems
* Learning MongoDb on the fly while pushing towards a deadline
 	* We had a slight learning curve when it came to learning a new db technology
    * Figuring out delete routes with node and making it sure we are passing the appropriate data objects was a challenge
* Styling React pages can be a chore when using a CSS framwork!
* We left some work on the table as we did not quite get the Quiz mode working


# How to get your own {FlashStash}?
If you'd like to set this project up on your own local server: 
* Fork and clone this repository
* Run `npm install` to install dependencies in both client and main project folder
  * Create a react build with `npm run build`  in the /client folder
  * Use `nodemon` to run the application
* Setup your database with Mongodb 
* Create .env file, inside set a "JWT_SECRET=wordOfyourchoice".
* To have a view of your database, use Mongo Compass or Robo 3T to manage the data in your MongoDb.


# Backlog for future development
Add advance styling so the app has a more evernote or Google keep theme
