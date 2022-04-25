# node-package-version

Node.js-based tool to modify the version in a `package.json` file.

Main use case is CI automation.

Note that this works similar to `npm version`, but without creating tags.

## Installation

node-package-version is not on NPM, but you can install it from GitHub:

### Using npm with git

```bash
npm install -g git://github.com/kagekirin/node-package-version.git
npm install -g git+ssh://git@github.com:kagekirin/node-package-version.git
npm install -g git+https://git@github.com/kagekirin/node-package-version.git
npm install -g git+ssh://git@github.com:kagekirin/node-package-version.git[#<commit-ish>]
npm install -g git+ssh://git@github.com:kagekirin/node-package-version.git[#semver:^x.x]
npm install -g github:kagekirin/node-package-version[#<commit-ish>]
```

### Using npm with the tarball

```bash
npm install -g https://github.com/kagekirin/node-package-version/tarball/main
```
