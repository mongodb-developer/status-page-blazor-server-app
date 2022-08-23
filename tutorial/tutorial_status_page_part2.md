# Building a Status Page with Blazor

When we build a new piece of software, there are often multiple systems and services involved.

Even though we do our best to make them as fail-safe as possible and also add other services to provide with details like server outages, errors in an app and other notifications, having all those small pieces of information on one single status page can make it easier to have a quick glance at what's going on.

The series consists of the following parts:
- Part #1: UI & Atlas Sync *(this tutorial)*
- Part #2: Retrieving status from healthchecks.io *(coming soon)*
- Part #3: Retrieving status from sentry.io
- Part #4: Retrieving status from Azure
- Part #5: Retrieving status from AWS
- Part #6: Retrieving status from Atlas

## Pre-requisites

## TODO: add links and text

- .NET SDK
- IDE (VS, Rider, etc.)
- MongoDB Atlas Account
- Microsoft Azure Web Service

For the future parts of this series you will also need an account for each of the systems we want to add:
- healthchecks.io
- sentry.io
- Amazon Web Services


![Mocked Status Page](images/mocked_status_page.png)

[//]: # (## Fetching data from MongoDB Atlas)

[//]: # ()
[//]: # (Up until now we only focused on the UI of the status page and filled it with static mock data. Now we'll make the first step to get a bit more dynamic. Continuing the top-to-bottom approach we'll build the next layer in this section: retrieving the status data from one central database. We will be using MongoDB Atlas for this.)

[//]: # ()
[//]: # (If you haven't done it while reading the pre-requisite section you should make sure to [register for a free Atlas account]&#40;https://www.mongodb.com/cloud/atlas/register&#41; now.)

[//]: # ()
[//]: # (![Create a New Project]&#40;images/create_a_new_project.svg&#41;)

[//]: # (![Name your Project]&#40;images/name_your_project.svg&#41;)

[//]: # (![Permissions]&#40;images/permissions.svg&#41;)

[//]: # (![Build a Database]&#40;images/build_a_database.svg&#41;)

[//]: # (![Deploy a Cloud Database]&#40;images/deploy_a_cloud_database.svg&#41;)

[//]: # (![Create a Serverless Instance]&#40;images/create_serverless_instance.svg&#41;)

[//]: # (![Database Deployment]&#40;images/database_deployment.svg&#41;)
