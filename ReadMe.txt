Camel Router Spring Project
===========================

To build this project use

    mvn install

To run this project with Maven use

    mvn camel:run


To deploy the project in OSGi. For example using Apache ServiceMix
or Apache Karaf. You can run the following command from its shell:

    osgi:install -s mvn:com.pawel.fuse.example/pawel-spring-webservice/1.0-SNAPSHOT

For more help see the Apache Camel documentation

    http://camel.apache.org/


Test in SOAP UI:
Soap consumer endpoint:
http://localhost:9191/cxf/claim


Restful producer endpoint:
http://localhost:9191/cxf/status/status/custId/A12345
http://localhost:9191/cxf/status/status/restcancel/B345678
