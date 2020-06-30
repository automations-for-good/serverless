# serverless-node
Serverless automations codebase written in Node.js


## Installation

To install dependencies simply run: `npm install`

### Run the Tests

If the project is setup correctly you should be able to run the existing set of tests:

```
npm test
```

### Run the Server

After ensuring the tests are running correctly, start the app:

Staging:

```
npm start:staging
```

Production:

```
npm start:prod
```

## Linting

All files are linted with ESLint: `npm run lint`

## Running Scripts

Staging:

```sh
node scripts/script-to-execute.js
```

Production:

```sh
node scripts/script-to-execute.js
```
