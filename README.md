Application demonstrating an AngularJS client talking to a Spring REST-powered backend.

## Building

To build the WAR file simply run `mvn package`. This puts the WAR
file in `target/spring-angularjs.war`.

You can deploy this WAR in any servlet container.

## Running

You can run the app in Jetty using `mvn jetty:run`.

Once started, the app is available at `http://localhost:8080`.