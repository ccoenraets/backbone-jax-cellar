# Backbone.js + Java Wine Cellar Application #

The Wine Cellar application is documented [here](http://coenraets.org).

This application provides an example of 
1. Building a complete RESTful API in Java using JAX-RS and Jersey.
2. Consuming these services using Backbone.js client application



Set Up:

1. Create a MySQL database name "cellar".
2. Execute cellar.sql to create and populate the "wine" table:

	mysql cellar -uroot < cellar.sql

3. Import the Dynamic Web Project in Eclipse.
4. Locate cellar.properties and make sure the JDBC connection string matches your database configuration
5. Run the project.