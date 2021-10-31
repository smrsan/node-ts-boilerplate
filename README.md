# node-ts-boilerplate

The Fundamental &amp; Required Scripts Before Starting A Clean TypeScript Project In Node.js

# Table of Contents

- [node-ts-boilerplate](#node-ts-boilerplate)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Scripts](#scripts)

# Installation

You need [pnpm](https://pnpm.io/) to install the node_modules (the dependencies of project):

```bash
$ cd /path/to/project
$ pnpm i
```

If you won't use [pnpm](https://pnpm.io/) as the package manager:

```bash
$ cd /path/to/project
$ rm -rf node_modules/ pnpm-lock.yaml
$ npm i # or yarn
```

# Scripts

| Script  | Description                                                                             |
| ------- | --------------------------------------------------------------------------------------- |
| `build` | Transpile/Compile typescript files into javascript files with the target ECMA standard. |
| `start` | Execute the project build files using pure node.js (without ts-node).                   |
| `dev`   | Execute the project typescript files using nodemon + ts-node.                           |
