# Simple CoffeeScript namespacing for the browser

Works well with joined (-j) coffeescript projects spread over multiple files

Usage:

    namespace 'some.name.space'
    class some.name.space.ClassName

And:

    SomeClass = use 'some.name.space.SomeClass'
    obj = new SomeClass