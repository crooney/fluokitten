# [Fluokitten](http://fluokitten.uncomplicate.org) - notable changes between versions

## 0.2.0

* Changed the order of arguments in uncomplicate.fluokitten.core/bind. Now the function is the last argument, previously it was the second. The protocols/bind function remains unchanged.
* join implementation for persistent collections and join no longer flattens the collection completely but only one level deep.
