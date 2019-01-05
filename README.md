# 11-friend-finder
Homework #11

Are you super person?  Having trouble finding people that are just as super as you?  Time to find that super friend to team-up with whether it's a partner in crime or the perfect mentor-sidekick relationship.  Look no further than the Super Friend Finder!  Using our super friend matching algorithm, you will find that super special someone you have been looking for!  Excelsior!

# Link


# Usage
To use the Super Friend Finder, visit our homepage and take our thorough and precise survey.  Immediately after submitting said survey, your perfect super friend match will be shown.  Also available is an API to access the network's users for researching purposes.  

# Requirements 
- Seperate files of server logic, storing friends, views and routing; in order to show modularity.
- A survey made of 10 questions to make distinct options for users.  
- The "server.js" file had the npm packages of "express", "body-parser" and "path." 
- JavaScript files that are seperate for routing "apiRoutes.js" and "htmlRoutes.js"
- Use appropriate POST and GET routes for serving HTML pages and API calls
- A file titled "friends.js" will store friends.
- Once the user has finished the survey, their best match will be shown to them. 

# Technologies

- JavaScript
- jQuery
- node.js 
- Express.js
- HTML
- Bootstrap

# Code Description
- First off, the "server.js" file sets up the Express server, which designates a port number, the npm packages that need to be implemented, along with routes that we have externalized.  
- I needed to create two seperate HTML files titled "home.html" and "survey.html that will be the front-end portion the friend finder, determining what the participant will view in regards to the homepage and the survey (that will also give the results of said survey).
- The two routing files that are titled "htmlRoutes.js" and "apiRoutes.js" are designated for functionality. For the back-end logic, depending on which request is being made, the response gets sent to the browser. The HTML routes display the survey and the homepage based on the URL that is accessed, and the API routes send back existing content in our server-side data or add new friends.  
- With each survey taken, the score is matched with other scores that have minimal difference, which sends the friend to the browser as a JSON object.
- Finally, a modal is triggered, showing the best match to the recent survey participant.  
# Author
Fernando Mendoza