![Apollographql](https://repository-images.githubusercontent.com/643852224/6d312bf2-90a0-4068-841c-743e8ac883b3)
# Kinsta - Hello World - Apollo GraphQL!


An example of how to deploy a GraphQL server using Apollo GraphQL on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

Kinsta automatically installs dependencies defined in your `package.json` file, during the deployment process.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application, Kinsta automatically creates a web process with `npm start` as the entry point. Make sure to use this command to run your server.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `npm build` command is run, followed by the `npm start` command.

## What is Apollo GraphQL
Apollo GraphQL Server is a flexible and powerful backend framework that enables developers to build and deploy GraphQL APIs with ease. More information is available on the [apollographql.com](https://www.apollographql.com/) website.
