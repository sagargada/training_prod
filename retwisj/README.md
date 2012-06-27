Spring Data - Key Value - Redis Twitter Example
===============================================

An improved Java implementation of the [Redis Twitter Clone](http://redis.io/topics/twitter-clone) using Spring Data. Tutorial available [here](http://static.springsource.org/spring-data/data-keyvalue/examples/retwisj/current/) and blog post [here](http://blog.springsource.com/2011/04/27/getting-started-redis-spring-cloud-foundry/)

Live instance available on [CloudFoundry](http://www.cloudfoundry.com/) [here](http://retwisj.cloudfoundry.com/)

Build
-----
The project creates a WAR file suitable for deployment in a Servlet 2.5 container (such as Tomcat). It uses [Gradle](http://gradle.org/) as a build system.
Simply type:

      gradlew build

or if you have gradle installed on your machine and in your classpath:

      gradle build

Start up an instance of the redis server, deploy your WAR and point your browser to (for the typical setup) [http://localhost:8080/retwisj](http://localhost:8080/retwisj)