## run with runner

mvn clean test -Dtest=MyRunner

## run with tag

mvn clean test "-Dkarate.options=--tags @MyTag" -Dtest=MyRunner

## run with env

mvn clean test "-Dkarate.env=dev" -Dtest=MyRunner

