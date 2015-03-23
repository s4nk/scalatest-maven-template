# scalatest-maven-template
Sample project showing how to run both ScalaTest and JUnit tests using Maven. Can be useful if you would like to start testing your code using Scala, but you already have some JUnit tests which you'd rather keep and run alongside the Scala tests. 

The project follows the standard Maven project structure:
- Java tests are located in `src/test/java`
- Scala tests are located in `src/test/scala`

In order to run all the tests simply use `mvn test`. Tests are executed by the maven-surefire-plugin, so the scalatest-maven-plugin is not needed. The template works nicely both in IntelliJ and Eclipse.


