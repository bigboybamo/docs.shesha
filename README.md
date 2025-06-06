# Shesha Documentation

This is the source of documentation for [Shesha](https://www.shesha.io/), hosted at [docs.shesha.io](https://docs.shesha.io/get-started/Introduction), powered by Docusaurus v2.

## Installation

Navigate to the website sub-directory

```
$ cd website
```

Run the below command to install node-modules

```
$ npm install package.json
```

### Local Development

To set up the local development environment

```
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

**Note:** The Search bar does not run in development mode and will be greyed out. To test the search, use the Build and Test commands below.

### Build

It would help if you verified all your changes with a local build.

```
$ npm run build
```

This command generates static content into the `build` directory. You can use the local builds to verify your added content before raising a PR.

### Test

```
$ npm run serve
```

This command is used to verify the content generated in the `build` directory. It acts as a simulator on your local machine to verify the actual build once the content is merged/deployed to the website.
