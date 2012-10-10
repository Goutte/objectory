##Objectory - thin object persistency layer built on top of Mongo-dart

Objectory provides typed, checked environment to model, save and query data persisted on MongoDb.

Objectory provides identical API for server side and browser applications (currently only Dartium platform supported, dart2js support blocked by several incompatibilities with *M1* spec.

###Getting started

- Clone Objectory from [github repository](https://github.com/vadimtsushko/objectory)
- Run **pub install** in the root of Objectory.

Now you may run server-side blog example: **/example/vm/blog.dart**. This example uses connection to free MongoLab account 

- Install MongoDb locally. Ensure that MongoDB is running  with default parameters (host 127.0.0.7, port 27017, authentication disabled)

Now you may run server side objectory tests in **/test/vm**

- While running local MongoDB process, start websocket objectory server. 
- Configure Dartium launches for **/test/browser/objectory_test.html** and **/example/browser/example/blog.html** In group Dartium settings uncheck *Run in checked mode* and *Enable debugging*.  

Now you may run browser tests and blog example (port of server-side example to browser)

See [Quick tour](https://github.com/vadimtsushko/objectory/blob/master/doc/quick_tour.md) for futher information