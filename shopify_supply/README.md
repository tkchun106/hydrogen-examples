# Shopify Supply

Shopify Supply is Shopify's official merch store. Now brought to you in Hydrogen!

# Hydrogen

Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.

[Check out the docs](https://shopify.dev/beta/hydrogen)

## Getting started

**Requirements:**

- Node v14+
- Yarn

```bash
yarn
yarn dev
```

## Testing

This application is tested with [Cypress](https://docs.cypress.io/).

Cypress is currently configured to run against a local dev server. See instructions for starting a dev server in the `Getting started` section.

### Running headless cypress

```bash
yarn cypress:run
```

### Running headed cypress

```bash
yarn cypress:open
```

## Building for production

```bash
yarn build
```

Then, you can run a local `server.js` using the production build with:

```bash
yarn serve
```
