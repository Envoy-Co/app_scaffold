Note: Run commands in the root app directory.

Compile the app for DEV
===============
1) `yarn install`
2) `yarn run watch`
3) `zat server -p dist` - Serves the app to your zendesk instance with `?zat=true`

Compile the app for PROD
===============
1) `yarn install --production`
2) `yarn run build:prod`

To run the tests
===============
1) `yarn install`
2) `yarn test`
