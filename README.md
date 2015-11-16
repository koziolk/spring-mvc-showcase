Spring MVC Showcase
-------------------
Demonstrates the capabilities of the Spring MVC web framework through small, simple examples.
After reviewing this showcase, you should have a good understanding of what Spring MVC can do and get a feel for how easy it is to use.
Includes project code along with a supporting slideshow and screen cast.

Changes to the original code base
-------------------
This version has slightly modified pom.xml file in order to test jboss-as-maven-plugin and compare it with
tomcat7-maven-plugin and jetty-maven-plugin.

To run the application:
-------------------	
In order to run the application on your local machine call:

#### tomcat7-maven-plugin
```bash
mvn tomcat7:run
```
or 

#### jetty-maven-plugin
```bash
mvn jetty:run
```
or 

#### jboss-as-maven-plugin
This option requires JBoss AS to be installed and running in standalone mode on your local box.
You can download it from: http://www.jboss.org/products/eap/download/
```bash
mvn jboss-as:deploy
```

Access the deployed web application at: http://localhost:8080/spring-mvc-showcase/

Useful links:
-------------------
* http://docs.jboss.org/jbossas/7/plugins/maven/latest/
* http://www.jboss.org/products/eap/download/
* http://tools.jboss.org/features/livereload.html
* https://confluence.jetbrains.com/display/IntelliJIDEA/Getting+Started+with+JBoss+Technologies+in+IntelliJ+IDEA

Note:
-------------------

This showcase originated from a [blog post](http://blog.springsource.com/2010/07/22/spring-mvc-3-showcase/) and was adapted into a SpringOne presentation called [Mastering MVC 3](http://www.infoq.com/presentations/Mastering-Spring-MVC-3).

A screen cast showing the showcase in action is [available in QuickTime format](http://s3.springsource.org/MVC/mvc-showcase-screencast.mov).
