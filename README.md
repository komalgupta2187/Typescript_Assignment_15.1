# Typescript_Assignment_15.1


● Create a service: configService which should make API url based on type of API url you want. Here you have to create for following:

○ University

○ Company

and set end-points and put your base url in your app-config.json

Notes:

Angular CLI is used to create app. So, use ng serve to run on localhost:4200

Created an interface class AppConfig which stores the base url and the endpoints

This is then registered in the provider list in the app.module ngModule
so that it is available anywhere (service or component)

Next, the interface is injected into the constructor of the service and used
to fetch data for the relevant components
