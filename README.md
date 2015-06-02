    NOTE: For the moment I'm alone on this trip, so if you're waiting to use this is clearly too soon.

# Architecture

Describing what I want to do in my freetime and when I want to work on something.

Some dreams that I hope it will happen sometime.

Clearly the aim is to have a complex stuff managed in the simplest way and that can scale up and down.

## Global ideas

A full stack that registers itself each component, as independent as possible. I have to find the right balance. Every component is API or UI, there can be components that mix the two by only combining two separate components.

Sample apps should be built, generators for components and a website. (sry, no Yo, Slush?)

As I hope I'll have something done next year IE9 is for the moment the lowest target. (IE8 end of support lifecycle is 2016)

Don't know if ES6 or TS, yet. Edge versions to be used. As IE11 end of support lifecicle is 2023 it will be required to be compiled to ES5 until then. ES6 classes are broken (constructor, super, etc.) and will be, anyway, required to be compiled so, a better choice would be a compiled language that aims to closer future and is widely used.

Thinking like MeanJS, just a bit different. Something already done?

Dependency Injection, Swagger, REST, Sync, microdervices

## Principles

- code reuse (that would be difficult in some situations)
- NO monolith
- only one html file
- offline first
- hyper-modular (I was asked why I'm using `hyper` because `modular` is `arhi`-sufficient. No, is not. I have to find the right words to explain my view.)

## Server side

### Techno

- NodeJS or IO.js
- HapiJS
- Mongoose or Dogwater
- Redis
- MariaDB and connected

### TODOs

#### Main app

- Knows to load plugins/modules/components/etc, the heck I want to name it

#### Components

There is any way to autoload them based on `package.json`? (in the spirit of Hapi)

- Home page
- Authentication API
 
#### Inspiration or usage

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


## Client side

To creat shims that enhance the current existing libraries

### Techno

- MarionetteJS (Backbone)
 0. here comes the struggle, to find the right combination of libs
 1. Marionette Toolkit
 2. Blazer
 3. RSVP
 4. jQuery
 5. Underscore
 6. Nested collections or find a valid lib for data
- Handlebars
- Gulp
- Browserify or ...
- Material + Bootstrap

#### Inspiration or usage

https://github.com/marionettejs/backbone-metal

https://github.com/thejameskyle/backbone.service

https://github.com/uplift/ExoSuit

https://github.com/mpneuried/iggy

https://github.com/muraken720/es6-backbone

https://github.com/thejameskyle/marionette-wires

https://github.com/thejameskyle/backbone-metal-classify


### TODOs

Independent components that loads when needed. CommonJS for apps, globals for the libs (hmmmm).

#### Components

- A base vendor file
- A base app that generates the main content and knows to load the rest

- Authentication UI
- Data grids and forms generated from schema

