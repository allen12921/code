###Decorator to expose local variables of a function after execution

Originally published: 2010-07-07 00:55:05
Last updated: 2010-07-07 22:01:23
Author: Pietro Berkes

Decorator to expose the local variables defined in the inner scope of a function. At the exit of the decorated function (regular exit or exceptions), the local dictionary is copied to a read-only property, `locals`.