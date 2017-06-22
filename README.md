There are two ways to test this server

"mvn clean test"

Will run just the unit tests. This is useful, for example, for build servers.

"mvn clean integration-test"

Will also run JavaScript tests on the client. Make sure you have Firefox (35.0.1) installed.