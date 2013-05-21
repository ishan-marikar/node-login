
#[Node-Login](http://node-login.braitsch.io) - Mysql

#### This is the same node login project but uses mysql as the database and jugglingdb as the ORM.


####A basic login & account management system built in Node.js with the following features :

* New User Account Creation
* Secure Password Reset via Email
* Ability to Update / Delete Account
* Session Tracking for Logged-In Users
* Local Cookie Storage for Returning Users
* Blowfish-based Scheme Password Encryption

***

####Node-Login is built on top of the following libraries :


* [Mysql](http://www.mysql.com/) - Database Storage
* [jugglingdb](https://github.com/1602/jugglingdb) - DB ORM
* [jugglingdb-mysql](https://github.com/jugglingdb/mysql-adapter) - Jugglingdb Mysql Adapter
* [Node.js](http://nodejs.org/) - Application Server
* [Express.js](http://expressjs.com/) - Node.js Web Framework
* [Jade](http://jade-lang.com/) - HTML Templating Engine
* [Stylus](http://learnboost.github.com/stylus/) - CSS Preprocessor
* [EmailJS](http://github.com/eleith/emailjs) - Node.js > SMTP Server Middleware
* [Moment.js](http://momentjs.com/) - Lightweight Date Library
* [Twitter Bootstrap](http://twitter.github.com/bootstrap/) - UI Component & Layout Library

***

A [Live Demo](http://node-login.braitsch.io) and [some thoughts about the app's architecture.](http://www.quietless.com/kitchen/building-a-login-system-in-node-js-and-mongodb/), Demo is based on the Node Login mongodb.

***

####Installation & Setup
This assumes you already have node.js & npm installed.
```
git clone git://github.com/braitsch/node-login.git node-login
cd node-login
npm install -d
node app
```
For testing purposes, I've provided a [database dump of all accounts here.](http://node-login.braitsch.io/print)  
Please note this list and the entire database automatically resets every 24 hours.

Questions and suggestions for improvement are welcome.