Java
====

First, you must use [``maven``](http://maven.apache.org/) to build the project and run the tests:

    mvn package

The SUT implementation can be seen in [``src/main/java/com/smartesting/coffeemachine/CoffeeMachine.java``](https://github.com/Smartesting/zest-publisher-samples/blob/master/java/src/main/java/com/smartesting/coffeemachine/CoffeeMachine.java)

JUnit
-----


To update the tests:

    zest-publisher -c junit.config --tests-only

The tests are generated in [``src/test/java/com/smartesting/coffeemachine/ProjectTest.java``](https://github.com/Smartesting/zest-publisher-samples/blob/master/java/src/test/java/com/smartesting/coffeemachine/ProjectTest.java)
