# OAuth Homework
## Here's what's done:

* Updated index.js with necessary code. 
* Link to "Login with facebook" added to main.handlebars
* package.json update
  * passport-oauth
  * passport-facebook

All necessary NPM's saved, just use 'npm install' in **cmd** to run. Recommend using **nodemon**; server is **8081**

## Errors:
Facebook link not working. Might be on APP settings, I'm not sure. Redirect added to app settings, so it probably has to do with line 89 in [index.js](https://github.com/mechurat/wk10-enhanced-trick-or-treat/blob/master/index.js)

### Error fixed.
It was on the facebook developer tools. Needed to create a test APP and add a platform -> web -> "http://localhost:8081" then add "http://localhost" to APP domains
