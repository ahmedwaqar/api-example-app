# Example App using AgenaRisk 10 Java API

## Initialization

git clone git@github.com:AgenaRisk/api-example-app.git

cd api-example-app

mvn clean compile

## Launch Example

mvn exec:java '-Dexec.mainClass="example.Demo"'

## Notes

* The project requires non-Java libraries to run
* Perform `mvn clean` to trigger downloading these libraries into `project/lib` directory
* On build, these will also be copied to `target/lib`
* Valid AgenaRisk Developer license (or a currently active Timed Trial) will be required to run this example