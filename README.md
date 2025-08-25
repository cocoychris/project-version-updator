# Project Version Updator

Project Version Updator is a CLI tool for updating project versions in package.json and other related files. It will also create a git commit for the new version.

## Installation

```bash
npm install -g project-version-updator
```

create a script in package.json to easily run the tool:

```json
"scripts": {
  "update-version": "node node_modules/@andrash/project-version-updator"
}
```

## Usage

To update the version, run:

```bash
npm run update-version 1.2.3
```

Use `+c` to create a git commit for the new version:

```bash
npm run update-version 1.2.3 +c
```

Use `+force` to force the version update:

```bash
npm run update-version 1.2.3 +force
```
