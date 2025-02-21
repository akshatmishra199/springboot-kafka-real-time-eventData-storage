# springboot-kafka-real-time-eventData-storage
installed and downloaded the apache kafka in C folder.
to start with kafka started the zookeeper service first using command "bin\windows\zookeeper-server-start.bat config\zookeeper.properties"
to start the broker service used the command "bin\windows\kafka-server-start.bat config/server.properties"

generated the project using spring initializr and added the dependency for apache kafka and lombok to reduce boiler plate code.
imported the project in eclipse.
to work with microservices, we need to add submodules and to start work with that update pom.xml file with code line "<packaging>pom</packaging>"
create module named as "kafka-producer-wikimedia"

make the module as springboot project by adding class SpringBootProducerApplication.
to verify the project setup run command "mvn clean install".
