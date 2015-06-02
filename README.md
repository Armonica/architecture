# Architecture

Describing what I want to do

Some dreams that I hope it will happen sometime.

## Global ideas

A full stack that registers itself each component, as independent as possible. I have to find the right balance. Every component is API or UI, there can be components that mix the two by only combining two separate components.

Sample apps should be built, generators for components and a website. (sry, no Yo)


## Server side

### Techno

- NodeJS or IO.js
- HapiJS
- Mongoose or Dogwater
- Redis

### TODOs

#### Main app

- Knows to load plugins/modules/components/etc, the heck I want to name it

#### Components

There is any way to autoload them based on `package.json`? (in the spirit of Hapi)

- Home page
- Authentication API

## Client side

### Techno

- MarionetteJS (Backbone)
- Handlebars
- Gulp
- Browserify or ...
- Material + Bootstrap

### TODOs

Independent components that loads when needed. CommonJS for apps, globals for the libs (hmmmm).

#### Components

- A base vendor file
- A base app that generates the main content and knows to load the rest

- Authentication UI
 
