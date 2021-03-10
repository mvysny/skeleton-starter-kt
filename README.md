# Skeleton Starter for Vaadin with Karibu-Testing

A simple "Hello, World" application in Vaadin and Java. A fork of the
[Skeleton Starter](https://github.com/vaadin/skeleton-starter-flow) but with the
[Karibu-Testing](https://github.com/mvysny/karibu-testing/) Vaadin Unit-testing demoed.

To access it directly from github, clone the repository and import the project to the IDE of your choice as a Maven project. You need to have Java 8 or 11 installed.

Run using `mvn jetty:run` and open [http://localhost:8080](http://localhost:8080) in the browser.

If you want to run your app locally in the production mode, run `mvn jetty:run -Pproduction`.

### Running Tests

Unit tests are implemented using [Karibu-Testing](https://github.com/mvysny/karibu-testing/).
Since the tests take only a couple of seconds to run, they're simply always run during the Maven test phase.
To run the tests, simply execute

```bash
mvn -C clean test
```

No license is needed and no browser is used, therefore the tests will also run in headless mode
in your CI environment.
