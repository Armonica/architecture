# Server side

Modularity should allow flexibility and drop-in replacements.

Would be interesting that models will deliver directly full CRUD and stuff (validation, schemas, etc.).

## Techno

- NodeJS or IO.js
- HapiJS
- Mongoose or Dogwater
- Redis
- MariaDB and connected
- In fact would be interesting to be able to connect to as many DB as wanted.

## TODOs

### Main app

- Knows to load plugins/modules/components/etc, the heck I want to name it
- Plugins delivers a default config.
- Knows to deliver static files and data depending on plugins

### Components

There is any way to autoload them based on `package.json`? (in the spirit of Hapi)

- Home page
- Authentication API
 
### Inspiration or usage

https://github.com/wrangr/hapi-prerender

https://github.com/kusha1988/Bachbone-and-Hapi

https://github.com/zetxx/hapi-droutes

https://github.com/poeticninja/hapi-plugin-lifecycle

https://github.com/Caligone/hapi-brickloader-demo

https://github.com/thegoleffect/actin

https://github.com/fhemberger/hapi-jsonapi

https://github.com/accosine/hapi-relax

https://github.com/SMARTDATASYSTEMSLLC/boilerplate-hapi

https://github.com/abiee/es6-hapijs

https://github.com/ubaltaci/hapi-plugin-boilerplate

https://github.com/firstandthird/hapi-auto-loader

https://github.com/lucadv/hapi-mongo-restful-service

https://github.com/hapijs/inert

https://github.com/mark-bradshaw/mrhorse

https://github.com/kashishgupta1990/HapiMongooseBoilerplate

https://github.com/jedireza/frame

https://github.com/Cron-J/User-Tenant

https://github.com/Newbourne/node-iso-browserify

https://github.com/stevenjmarsh/hapi-starting-point

https://github.com/Jasonspd/template-hapi

https://github.com/johnmanko/hapi-socketio-router

https://github.com/validkeys/hapi-skeleton

https://github.com/ben-bradley/generator-chop

https://github.com/ben-bradley/generator-ham

https://github.com/FernandoCagale/hapi-api
