---
id: version-0.11.x-quickstart
title: Create client and server application from template
sidebar_label: Create a new app
original_id: quickstart
---

You can use the Graphback CLI to generate a new GraphQL project in minutes.

Initializing with npx:

```sh
npx graphback-cli init <project-name>
```

Or by installing Graphback CLI globally:

```sh
npm install -g graphback-cli
graphback init <project-name>
```

The CLI will ask you to choose from one of two templates:

- `apollo-fullstack-ts`: Apollo GraphQL server and React client using TypeScript and PostgreSQL.
- `apollo-runtime`: Apollo GraphQL server with in-memory Graphback schema and CRUD resolvers.

In a few seconds you should have an empty GraphQL application.

### Next Steps

See [Defining your Data model](./datamodel.md) for how to design your data model.

To change the default application configuration see [Graphback Config](./config.md).

Once your data model is complete, run `graphback generate` from your project to generate a GraphQL schema and API.

You can migrate your database to match your schema by running `graphback db`. See [Database Migrations](../db/migrations.md) for more.