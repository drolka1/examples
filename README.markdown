# Paremus Service Fabric #
### A distributed OSGi based Cloud platform ###

[Terminology and Concepts](https://docs.paremus.com/display/SF19/Terminology+and+Concepts)

##Examples: 

* [helloworld](https://github.com/paremus/examples/tree/master/helloworld) - A simple sequence of Hello World examples which demonstrate:
    * The light-weight Nimble R5 environment with Declarative Services and Blueprint 
    * The equivalent 'Fabric' (OSGi Cloud) - example
    * Features and Resource Contracts 
    * Use of the Fabric's Remote Services
    * Upgrade and RollBack capabilities
    * The Fabric's dynamic Scale Out / Replication behavior.
    * The use of fibre Assessors
* The [rest](https://github.com/paremus/examples/tree/master/rest) REST example demonstrates Fabric deployment and dynamic wire-up of REST based Services.
* The [datanucleus](https://github.com/paremus/examples/tree/master/datanucleus) demonstrates a hybrid heterogenous System - consisting of Play, Camel, the DataNucleus ORM & MongoDB - all dynamically deployed by the Service Fabric as OSGi components.
* The [nginx](https://github.com/paremus/examples/tree/master/nginx) example demonstrates the Fabric deployment and dynamic configuration of nginx endpoints. 
* [trivial-calc](https://github.com/paremus/examples/tree/master/trivial-calc) - A simple OSGi remote services demonstration; this leveraging the Paremus Remote Service Admin (RSA) implementation [Discovery provider - SLP, Distribution  provider - EssenceRMI].

##Tooling:

Try out [Bndtools](http://bndtools.org/)
