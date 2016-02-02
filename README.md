# MEANr
A MEAN relational stack - Mysql Express Angular Node relational

DEMO: https://meanr.io

This project is split into three main repositories. See the readme of each repo for getting started:
 - Express API server ([MEANr-api](https://github.com/christurnbull/MEANr-api))
 - AngularJS Web App ([MEANr-ng](https://github.com/christurnbull/MEANr-ng))
 - Ionic Mobile App ([MEANr-ion](https://github.com/christurnbull/MEANr-ion))
 
#### Features
An alternative to mean.io and meanjs.org that's a bit MEANr.
 - JSON Web Tokens - expiring and persistent refresh tokens
 - Social logins
 - Emal account confirmation/password reset
 - Admin dashboard 
 - Strict JSON Schema, ACL, Socket.io, IDS, audit logging...
 - Full list: https://meanr.io/#!/about


#### Why does the world need another MEAN stack?

Because sooner or later you will realize MongoDB probably [isn't the right choice.](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongod)

The relationship between data is as important as the data itself. Life is a lot easier with ACID transactions.

And [cookies aren't ideal](http://sitr.us/2011/08/26/cookies-are-bad-for-you.html) - using [tokens](https://auth0.com/blog/2014/01/07/angularjs-authentication-with-cookies-vs-token/) is a great way to serve AngularJS webpages and Ionic mobile apps.


#### Dependencies

- Mysql 5.x
- Express 4.x
- Angular 1.4.x
- Node 4.2.x


#### Possible future developments
- gunmail webhooks
- charts for JSNLog
- ignore jsnlog when user messes with dom
- refresh provider persistent tokens
- add user capabilities/permissions viewer to route view
- activity audit log socketio requests
- audit log geodata map
- admin performance - reduce ng-hide/ng-show and filters in ng-repeat
- whatever you can fork and pull!

#### Support

Please open an issue in the relevant repository for support.

#### Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and open a pull request in the repository.

#### License

The code is available under the [MIT license](LICENSE.txt).
