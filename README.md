![cf](http://i.imgur.com/7v5ASc8.png) lab-36-fullstack-oauth
====

# To Submit this Assignment
* fork this repository
* write all of your code in a directory named `lab-` + `<your name>` **e.g.** `lab-duncan`
* push to your repository
* submit a pull request to this repository
* submit a link to your PR in canvas
* write a question and observation on canvas

# Description
* register with the GOOGLE Developer Portal
 * create a new app 
 * set it up to have permisions with `Google +`
 * add OAUTH Cradentials
  * GET CLIENT ID
  * GET CLIENT SECRET
* reafactor the slugram backend with the ng-template or your slugram-frontend
 * make a `.cleint.env` (by copying the frontend .env)
  * set a `GOOGLE_CLIENT_ID`
 * set the `__GOOGLE_CLIENT_ID__` in your webpack config.js
 * merge your package.json files 
  * make sure all the dependencies are there
  * change the npm scripts to reflect the class lecture (aka. start-watch && build-watch && frontend-test)
 * make a `.server.env` (by copying the backend .env)
  * set  `GOOGLE_CLIENT_ID`
  * set a `GOOGLE_CLIENT_SECRET`
 * copy your frontend tests into a dir named **client-test**
  * rename the the paths in the karma.config.js accordingly
* dont forget anything from lecture
* get all of your tests to pass
* add the express static server to your server.js

