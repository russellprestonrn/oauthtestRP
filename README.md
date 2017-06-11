# Sample JS Simple Application

## Setup

The Sample JS Simple Application is hosted as a static web app.

## Hosting
````
npm install
npm run serve
````

## Launching the app

The Sample JS Simple Application can be launched using the HSPC Sandbox or an EHR simulator of your choice.

1. Open the HSPC Sandbox at <https://sandbox.hspconsortium.org> (create an account if you don't have one)
2. Select your sandbox instance (create a sandbox if you don't have one)
3. From the *Launch Scenarios* screen, build a launch scenario
4. Select a persona (a persona is a simulation of a user account such as a doctor or patient)
5. Select a patient
6. Enter custom launch values of
    * my_web_app
    * http://localhost:8080/launch.html
7. Select *Just Launch*
8. Complete the OAuth flow

## Dynamic Registration
The app contains dynamic registration at:

* manifest: <http://localhost:8080/.well-known/smart/manifest.json>