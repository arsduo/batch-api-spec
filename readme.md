## Batch API Specification

As more and more people implement versions of the [batch API](http://github.com/arsduo/batch_api) initially implemented in Rails, inspired by Facebook, the time has come to set a standard for how these systems should behave.  Via this standard, an app developer should be able to switch from a Rack-based solution to an [external Scala batch server](https://github.com/chad/batch_api_server) or even an [implementation baked into Nginx](https://github.com/i0rek/butcher) without changing a line of client code.

The attached document (rfc.txt) specifies, in IETF RFC-like format, the project background and how a Batch API system (or client) should behave.

### Contributing

Feature suggestions, formatting improvements (there's a lot to learn about writing RFCs), issues, etc. -- all very welcome.  Just submit a pull request!