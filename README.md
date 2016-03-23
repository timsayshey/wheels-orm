# Wheels ORM
Finally an ORM for the rest of us

## v0.1 Alpha

This is the initial attempt to separate the CFWheels ORM from the core into it's own module.

## Progress

Because the ORM and the core are so coupled this is quite a difficult task.

Currently my strategy has been to setup CFWheels and strip away everything except what is needed for the model method to work.

To get it working just edit the datasource in the Application.cfc and called the index.cfm. May require a bit of debugging to get working but it works for me.

## Goals

* v0.1 - Still coupled with Wheels framework but most has been stripped away
* v0.2 - Remove remaining unneccessary wheels methods
* v0.3 - move models, cache, etc. into it's own application scope, separate from application.wheels
* v1.0 - Add simple config file and test dropping it into a FW/1 and Coldbox application (Will probably need to change function naming to prevent collisions)
* v2.0 - Remove models from Wheels and switch the core over to rely on WheelsORM

## Contribute

This is a starting point and I would appreciate any issues and contributions. I'm not picky.
