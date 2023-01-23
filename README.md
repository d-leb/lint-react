# lint-react
A library for linting TypeScript and JavaScript ReactJS projects. Linting is achieved using a combination of eslint, stylelint and prettier. ESlint is a code quality inspector, stylelint is a linter
for CSS and prettier is a code formatter. This library can bootstrap a project with linting support and allows you to customize settings in a non-proprietary way. This library is designed to be used
as a dependency in a project. It is not designed to be used as a standalone project. If you have suggestions or have any problems, please open an issue on the
[d-leb/lint-react issues board](https://github.com/d-leb/lint-react/issues).

To use this library, add the library to your project as a ***devDependency***.

Install with npm:

```
npm install --save-dev @d-leb/lint-react
```

Install with yarn:

```
yarn add -D @d-leb/lint-react
```

Add the following scripts to your project's package.json file.

```
  "scripts": {
    "name": "command"
  },
```

Create your BLAHBLAHBLAH configuration files by running the following command.

Create default configuration files in npm:

```
npm run defaults
```

Create default configuration files in yarn:

```
yarn defaults
```

Update the following config files located in the root of your project to suit your needs:

| Variable Name | Description |
| --- | --- |
| tsconfig.json | Settings for TypeScript compilation used by SWC |

Using npm or yarn you can run the following commands.

### start

The Development environment will be started and your default web browser should open or you can open any web browser on your development machine and visit
[http://localhost:3000](http://localhost:3000) to view it in the browser.

### defaults

Default BLAHBLAHBLAH configs are placed in the root directory of the project.

## Getting Started with library development

These instructions will get your copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

NodeJS is required to run commands and scripts. Both software and installation instructions can be found at [NodeJS.org](https://nodejs.org/). Using the LTS version is recommended.

Nvm is used as the node version manager to ensure the correct version of NodeJS is used with this project. For specific installation instructions, visit the
[nvm-sh/nvm repo](https://github.com/nvm-sh/nvm) and follow the instructions for installation. For Windows, you will need to install Windows WSL or use the bash system installed with git and manually
add the ~/.nvm folder to your user PATH and .bash_profile file. If you choose to not use nvm, you will need to manually install the correct version of NodeJS.

Yarn is used as the package manager and to initiate scripts. You can install Yarn globably by running the command below after you have NodeJS installed.

```
npm install -g yarn
```

### Installing

Install the specific NodeJS version dependencies.

```
nvm install
nvm use
npm install -g npm
```

Setup package dependencies.

```
yarn install
```

Be sure to install recommended extensions for VSCode. The project workspace settings are already pre-configured. This will allow VCode to automatically format your code.

## Linting

Github will automatically lint the project before allowing a PR to be merged. You can manually run all tests by running the following script.

```
yarn lint
```

## Built With

- [ESLint](https://eslint.org/) - Code quality inspector
- [Prettier](https://prettier.io/) - An opinionated code formatter
- [Yarn](https://yarnpkg.com/) - Package management

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

Patch level is automatically updated on every merge into the develop branch.

## Authors

- **David LeBlanc** - _Initial work_ - [d-leb](https://github.com/d-leb)

See also the list of [contributors](https://github.com/d-leb/lint-react/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
