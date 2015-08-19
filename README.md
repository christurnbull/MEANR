# MEANR stack
The MEANR Stack - Mysql Express Angular Node Relational

An alternative to mean.io and meanjs.org that's a bit more MEANR

WIP

Features

Relational database with transactions - using sequalize
JSON Web Tokens - instead of cookies
Passport social logins
User sign up/email confirmation & password reset
Scheduled tasks
Custom logging
API endpoint hijack protection
Angular client caching, messages, resource
Bootstrap
Grunt build tools - familiar layout to the Yeoman angular base project

Why re-invent the wheel?

Because sooner or later you'll realize MongoDB isn't the right choice.
The relationship between data is as important as the data itself - ACID transactions are absolutely required.

http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/comment-page-2/
https://rclayton.silvrback.com/means-great-but-then-you-grow-up

And cookies aren't ideal - using tokens simplifies serving mobile apps (so you can use the same API server to serve ionic or famo.us apps as well as your Angular webpage)

https://auth0.com/blog/2014/01/07/angularjs-authentication-with-cookies-vs-token/

http://sitr.us/2011/08/26/cookies-are-bad-for-you.html


Plus I wanted more features and I wasn't keen on the project file structures


Built with:

Mysql 5+
Express 4+
Angular 1.4+
Node 10+
