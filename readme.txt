This is a web app that allow user chatting with each other on this web app. It requires to deploy it on a server and connect to a relational DB before using.
If it's properly deployed, users can register an account then chat with any other registered user. It can be a one-to-one chatting or a multiple users chatting.

Installation step.
1.Go to the file Capstone/src/main/resources/application.properties
2.Change "spring.datasource.url" attribute to your mysql link and update the spring.datasource.username/password.
3.If not using mysql, it needs to change the library path in pom.xml and "spring.jpa.properties.hibernate.dialect" and "spring.datasource.driverClassName"
4.Generate a war file then deploy it on tomcat server.
5. Initiate the tomcat server.