# What is the WordPress REST API?

We look at the specifics of the WordPress REST API, including its infrastructure and endpoints, its authentication methods and the concept of hypermedia. We also introduce you to the team behind it.
The WordPress REST API allows access to a website’s data, including users, posts, and taxonomies. In the past, developers needed to use WordPress’ built-in theme system and administration panel to display and edit content on

The REST API decouples the WordPress backend from the frontend, allowing developers to use it as an application platform: WordPress is used for data entry and storage, and the frontend can be built in any programming language. The REST API transforms WordPress into a headless CMS.

The REST API decouples the WordPress backend from the frontend, transforming it into a headless CMS.

## Endpoints

The WordPress REST API uses two forms of authentication:

In addition, there is a Basic Authentication method for external clients. However, this is only recommended for development environments as it involves passing your username and password on every request, and giving your credentials to clients.

Who should be allowed to update content on a site or retrieve data, and under what conditions?