# goodbits
A node js project to demonstrate authorization with an authorization server.
# Instructions
- clone the project
- run `npm install` to install dependencies
- run `node index.js` to run the project
- Since we are using Github authorization server, once the app starts, one can go to http://localhost:8080/ , authorize with Github, and end up on the welcome page, which displays the greeting!

# API Documentation
 We are using the git api "https://api.github.com/user", after getting access_token, to fetch user details.
 -       url: "https://api.github.com/user",
         type: "GET",
         headers: {
           "Authorization": 'token ' + access_token
         }

_thank you_
