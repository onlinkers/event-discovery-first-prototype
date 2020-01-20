# llwa-first-prototype
[![Netlify Status](https://api.netlify.com/api/v1/badges/3b398591-ef2c-400a-ade2-f02e6f27c42f/deploy-status)](https://app.netlify.com/sites/link-link-web-app/deploys)


The first prototype of the LINK LINK Web App, an event-tracking web application created as part of a personal project for a group of students based in Vancouver. The team organization page can be viewed at:

https://github.com/link-link-webapp

- - - -

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

1. Clone the remote repository into a local environment

2. [Install all dependencies](#dependency)

3. Run both vue application and express backend

Vue provides a user interface (BETA) that allows deploying the project on an optionally specified port on *localhost:PORT_NUM*. The Vue UI can be accessed by running the command below on the project root:

```
vue ui
```

Otherwise, locally run the app by the following vue commands:

#### Compile the vue application with hot reloading

```
npm run serve
```

#### Compile and minify the vue application for production

```
npm run build
```

#### Run node API

```
npm start
```


### Running the tests

Unit testing on the project will be done with JEST. JEST can be installed by adding it as a dependency to the project by running the following command:

```
npm install --save-dev jest
```

"--save-dev" ensures that JEST is only required as a dependency during the development stage of the project

Instructions on installing and using JEST can be found on the [original documentation](https://jestjs.io/docs/en/getting-started).

- - - -

## Built With

* [Vue.js](https://vuejs.org/v2/guide/) - The web framework used

### Production Dependencies

The project is a full-stack MEVN (Mongo, Express, Vue, Node) built fully on the Vue framework, 

The project currently requires the following packages as dependencies in order to _deploy_:

> [vue-router](https://router.vuejs.org/guide/#html) (url routing)

> [vuex](https://vuex.vuejs.org/guide/) (storage management)

> [bootstrap-vue](https://bootstrap-vue.js.org/docs) (display)

### Additional Dependencies

The project uses [sass-loader](https://vue-loader.vuejs.org/guide/pre-processors.html#sass) to compile SASS [node](https://github.com/sass/node-sass) files into readable CSS

<a name="dependency"></a>To install all the dependencies, simply clone the project and run the following command in the project root folder. 

```
npm install
```

End with an example of getting some data out of the system or using it for a little demo

- - - -

## MapBox

- - - -

## Contributing

Contributions are only accepted from members of the [team](https://github.com/link-link-webapp). Instructions to start contributing are as follows:

1. Clone the remote repository into a local environment
2. Make the appropriate edits and additions
3. Make a pull request with a detailed commit message of what additions were made

--> Pull requests will be accepted after being reviewed and after unit tests are conducted

## Authors

