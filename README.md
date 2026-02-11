Requires Java 25 and maven 3.9.12
To recreate error run
mvn site

[ERROR] Failed to execute goal org.apache.maven.plugins:maven-site-plugin:3.12.1:site (default-site) on project my-app: Error generating maven-checkstyle-plugin:3.6.0:checkstyle report: Failed during checkstyle configuration: Exception was thrown while processing /home/klsfag03/lab/my-app/src/main/java/com/mycompany/app/ExtendsBase.java: IllegalStateException occurred while parsing file <path>/my-app/src/main/java/com/mycompany/app/ExtendsBase.java. 5:12: mismatched input '(' expecting ';': InputMismatchException -> [Help 1]
