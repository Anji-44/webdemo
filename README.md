# learn-docusaurus

The **learn-docusaurus** repository is dedicated to learning and exploring Docusaurus, an open-source project for building, deploying, and maintaining documentation websites. This repository serves as a collection of projects built using Docusaurus, showcasing various use cases and examples that can be helpful for anyone looking to learn or improve their skills in using this powerful documentation framework.

## About Docusaurus

[Docusaurus](https://docusaurus.io) is a powerful documentation framework that makes it easy to maintain and deploy documentation websites.

# Create first docs only website

This website is using [Docusaurus](https://docusaurus.io/), to create docs-only website.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## License

This repository is licensed under the BSD 3-Clause License. For more details, see the [LICENSE](/LICENSE) file in the repository.
