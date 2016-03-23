# Wheels ORM
Finally an ORM for the rest of us

## v0.1 Alpha

This is the initial attempt to separate the CFWheels ORM from the core into it's own module.

Because the ORM and the core are so coupled this is quite a difficult task.

Currently my strategy has been to setup CFWheels and strip away everything except what is needed for the model method to work.

To get it working just edit the datasource in the Application.cfc and called the index.cfm. May require a bit of debugging to get working but it works for me.

This is a starting point and I would appreciate any issues and contributions.
