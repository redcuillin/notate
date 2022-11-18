# Notate
www.notestotab.com

This app aims to provide an accurate tool for plotting notation and getting guitar tablature out in the browser.

![intro gif](./intro-gif.gif)

## Running locally

Modifications for redcuillin fork:
Had to enable npm corepack and update yarn globally in the following way to get yarn to work again:

`$ corepack enable`
`$ yarn init -2`
`$ yarn`

First run of yarn migrates yarn 1 and enables compatibility node-modules linker.

Since it's just essentially an ejected `create-react-app` project, you can use:

`yarn && yarn start`

Go to localhost:3000

## Linting 
Eslint + prettier

`yarn lint`

## Testing
Enzyme, Jest and Cypress.

Unit: `yarn test`

Cypress: `yarn cypress:run`
