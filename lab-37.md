![cf](http://i.imgur.com/7v5ASc8.png) lab-37-fullstack-oauth
====

# To Submit this Assignment
* continue from lab 36
* push to your repository
* submit a pull request to this repository
* submit a link to your PR in canvas
* write a question and observation on canvas

# Description
* create a `/api/auth/oauth_callback` route to handle the OAUTH callback from the google authentication server
* write a googleOAUTH middleware to retrive the users following information... 
 * access token 
 * refresh token
 * token expiration time
 * email
 * google id
* upon successful authentication
 * if the user allreay exits in the database
   * generate a user token using
 * if the user does not yet exits in the database
   * create a new user with the google info
    * genarete a token timestamp that dates the time the token was recieved
     * generate a user token
 * redirect your app to the login page of your app and pass the the token back in a query string
