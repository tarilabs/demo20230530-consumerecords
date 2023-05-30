per https://docs.drools.org/8.39.0.Final/drools-docs/docs-website/drools/getting-started/index.html

- set maven.compiler.release=17
- elide ecj from dep tree
- replacing class with record for consumption/pattern match
- need to instrument sys property to avoid kie-maven-plugin use ecj
