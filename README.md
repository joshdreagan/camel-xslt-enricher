# camel-xslt-enricher

Example showing how to do enrichment in camel utilizing the `org.apache.camel.util.toolbox.XsltAggregationStrategy`.

## Building the code

```
mvn clean install
```

## Testing

There is a JUnit test inside the project that will run when the project is built (unless the `-DskipTests` arg is passed). It does no assertions, but prints the output to the console so you can see it. Alternately, you can run the project with `mvn -DskipTests camel:run` and then open a browser to [http://localhost:8080/catalog](http://localhost:8080/catalog) to see the rendered HTML.
