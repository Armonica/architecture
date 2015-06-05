  NOTE:
   
    For the moment I'm alone on this trip, so if you're waiting to use this is clearly too soon.
    
    I'm searching for people that think this trip is relevant and wants to participate.
    
    Lets try thinking the same way.
    
    No `Grammar Nazi`, No killing procedures, No best practices (but ours), lets innovate and be cool. 
    

# Architecture

Describing what I want to do in my freetime and when I want to work on something.

Some dreams that I hope it will happen sometime.

Clearly the aim is to have a complex stuff managed in the simplest way and that can scale up and down.


# TOC

Everything should be spliced in files. Not ready, yet.

- [Global Ideas](https://github.com/Armonica/architecture/tree/master/ideas)
- [Principles](https://github.com/Armonica/architecture/tree/master/principles)
- [Monetization](https://github.com/Armonica/architecture/tree/master/monetization)
- [Server side](https://github.com/Armonica/architecture/tree/master/server)
- [Client side](https://github.com/Armonica/architecture/tree/master/client)


# To be moved to chapters

A JSON object can be converted to schemas, Mongoose or JSON Schema using https://github.com/Nijikokun/generate-schema

In this case an API can be built by example and generate the needed schemas.

There are other converters like 
- https://github.com/tlivings/enjoi to generate JOI schemas from JSON Schema
- converting JSON Schema to Mongoose: https://github.com/jon49/json-schema-to-mongoose
- JOI to Mongoose: https://github.com/HelloWallet/joi-mongoose

Taking that in consideration starting from a full API example and a way to load everything automatically from the generated files a very flexible API can be built and used.
 
Thinking that found libraries are not complete or does not fit perfectly the needs of this project, those libraries can be forked and improved. 

As the server-side of the application will be full API, JWT authentication makes sense and few seeds can be used:
https://github.com/Cron-J/JWT-Hapi-Mongoose-Mongodb-with-email-verification-and-forgot-password
https://github.com/Cron-J/JWT-Hapi-Mongoose-Mongodb
https://github.com/viniciusbo/hapi-suricate


---

Also JSON Schema can be used for validation on server and client side.

---

For client side there are several libraries that uses JSON Schema to generate interface elements, most notably Alpaca: https://github.com/gitana/alpaca

If Backbone/Marionette will be use we can use for JSON Schema https://github.com/atsid/schematic-js or  https://github.com/dnemoga/Backbone.Schema

That being said based on JSON Schema a full application can be built, server and client, with database schema, tables and forms and with validation on both sides. 

HapiJS will be used to load modules transparently, and to manage and validates routes for Mongoose.


