# Contributor

[Joseph DIOUF](http://joedigital.fr)
**Dev Back-End**

# Hapi JS Template

A template that allows you to have a basic foundation and quickly create your project with [HapiJS](http://hapijs.com).

## The FOLDERS :

### config

Server config file inside here. This config folder file loaded using [Config module](https://github.com/lorenwest/node-config).
Read its documentation for more details.

### Ressources

For each table in our database, we will create its resource here and which will contain the following 7 queues:

- dao.js ->
- controller.js
- model.js
- router.js --> ressource router ([HapiJS route](http://hapijs.com/tutorials/routing))
- validator.js --> router validator ([HapiJS route validation](http://hapijs.com/tutorials/validation))
- pre.js --> method for processing request before it reaches the controller ([HapiJS pre-handler](https://hapijs.com/api/16.6.2#route-prerequisites))
- mapper.js

### Utils

You can put your utility file here, eg: db connection, logger, etc.

## Code Style Checker:

There is **.eslintrc** file included.
