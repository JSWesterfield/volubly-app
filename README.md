# Volubly App

Volubly is a Angular 7 application for the purpose of messaging and Voice over IP service, allowing users to send text messages, voice calls, recorded voice messages, video calls, images, documents, and user location.

![whatsapp-mirror-img](https://cdn.vox-cdn.com/thumbor/JGRpwGpn1T9VpgeQ-Tu2s7ACihM=/0x0:1600x1000/1200x800/filters:focal(672x372:928x628)/cdn.vox-cdn.com/uploads/chorus_image/image/61917983/395757627359586.0.png)

<a href=""><p align="center"><img src="https://cdn-images-1.medium.com/max/1040/1*fFUJd7moWtjvMZ5dE-A80g.gif" alt="whatsapp" width="240"></p></a>

### Prerequisites
Install PostgreSQL following the [official instructions](https://www.postgresql.org/docs/9.3/tutorial-install.html).

### Run instructions

```yarn
Run yarn
    $ yarn install
Run codegen to generate TypeScript types
    $ yarn generate
Run start
    $ yarn start
```
Note that the server is using a common Cloudinary storage for uploading images. To change Cloudinary URL, please edit the `.env` file.

## Installation

Use the package manager [npm](https://volubly.com/stable/) to install volubly-app.

```npm
npm install volubly-app
```

## Usage

Implements the same functionality as WhatsApp for mobile devices

```javascript
//adding stuff later
foobar
to 
foo
extracted from
barfoo

```

## Built With

* [Angular](https://angular.io/docs) - TypeScript-based open-source web application framework from Google. Version 7.2.

* [Typescript](https://www.typescriptlang.org/docs/handbook/angular.html) - Strict syntactical superset of JavaScript, and adds optional static typing to the language. Integrated within Angular 7

* [NPM](https://docs.npmjs.com/) - Dependency Management
* [yarn](https://docs.npmjs.com/) - Dependency Management
* [Angular CLI 7.3.2](https://angular.io/cli) - command-line interface tool that you use to initialize, develop, scaffold, and maintain Angular applications
* [ExpressJS](https://expressjs.com/en/starter/installing.html/)- fast, unopinionated, minimalist web framework for node
* [GraphQL](https://graphql.org/learn/) - Query language for your API, and a server-side runtime for executing queries by using a type system you define for your data
* [Apollo-GraphQL](https://www.apollographql.com/docs/) - GraphQL server for Express for replacing many inflexible APIs with a single versatile query system

* [GraphQL-Subscriptions](https://www.apollographql.com/docs/react/advanced/subscriptions) - A small module that implements GraphQL subscriptions for Node.js

* [GraphQL-Modules](https://graphql-modules.com/docs/introduction/getting-started) - a toolset of libraries and guidelines dedicated to create reusable, maintainable, testable and extendable modules out of your GraphQL server

* [GraphQL-Code-Generator](https://graphql-code-generator.com/docs/getting-started/) - CLI tool that can generate TypeScript typings out of a GraphQL schema

* [TypeORM](https://github.com/typeorm) - ORM for TypeScript and JavaScript (ES7, ES6, ES5). Supports PostgreSQL. Works in NodeJS

* [Angular Material UI](https://material.angular.io/) - Material Design components for Angular

* [Postgresql](https://www.postgresql.org/docs/) -  Open source object-relational database 
Modules

* [Body-parser](https://github.com/expressjs/body-parser) - Node.js body parsing middleware

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Authors

* **Jake Westerfield** - *Primary Work*

## License
[MIT](https://choosealicense.com/licenses/mit/)
