# camel-factory
OSGi ManagedServiceFactory implementation to support deploying Apache Camel Contexts and Routes via ConfigurationAdmin. 
The facility includes:

* A CamelFactory bundle that reacts to configuration file deployments or updates
* A UI for managing deployment of configuration files built to work with the CamelFactory bundle
* Web Services used by the management UI for working with the datastore and communicating with the CamelFactory service
* A UI for monitoring execution of Camel Routes deployed by the RouteFactory
* Web Services used by the monitoring UI for working with the datastore
* A plugin framework for defining RouteBuilder implementations used by the CamelFactory for creating Camel Routes
* Reference RouteBuilder implementatoins consumable by CamelFactory
* A plugin framework for conneting datastore implementations used by CamelFactory for storing configuration and logging content
* Reference implementations of datastore plugins for connecting to sample storage mechanisms including database and file based options
* Database scripts to create tables used by the database centric datastore plugins for various providers

Apache Camel is a registered trademark of the Apache Software Foundation.
