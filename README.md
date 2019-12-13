# Description
Based on AirBnB linting rules

# Installation

## Before installation
This package is private, so you need to be authentificated. Create a personal access token with `read:packages` and `repo` scopes ([manual](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line)). Store this token in your password manager and set it as environmental variable `GITHUB_TOKEN={your_generated_token}`.
Also don't forget to create a `.npmrc` file:
```
//npm.pkg.github.com/:_authToken=${GITHUB_TOKEN}
@carnect:registry=https://npm.pkg.github.com/Carnect
```
Afterwards, you can install the package.

## Install from the command line:
```
npm install @carnect/tslint-config-carnect@1.0.0
```

## Install via package.json:
```
"@carnect/tslint-config-carnect": "1.0.0"
```

