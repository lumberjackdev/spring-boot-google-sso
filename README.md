# Spring Boot with SSO Example
This example shows how to use Spring Boot with SSO using Google authentication.

To run this example:
1. Go to the [Google sign-up page](https://developers.google.com/identity/sign-in/web/sign-in#before_you_begin) to get a client ID and secret.
1. Edit `gradle.properties` to fill in the the client ID and secret you just generated
1. Run `./gradlew bootRun` and navigate to `http://localhost:8080/actuator` and you'll be prompted to sign in with Google