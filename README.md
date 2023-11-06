# docusaurus-plugin-fathom

[Fathom](https://usefathom.com/ref/ZB4OSQ) analytics plugin for [Docusaurus v2](https://github.com/facebook/docusaurus).

> 🔥 Fathom is a privacy-focused website analytics. Get 10\$ off to try it with this link https://usefathom.com/ref/ZB4OSQ. 🔥

## Installation

Run the following command to install docusaurus-plugin-fathom in your project:

```sh
# With npm
npm install docusaurus-plugin-fathom --save

# With yarn
yarn add docusaurus-plugin-fathom

# With pnpm
pnpm add docusaurus-plugin-fathom
```

## Configuration

Edit the configuration in your site's `docusaurus.config.js` file:

```js
// docusaurus.config.js

module.exports = {
  plugins: [require.resolve('docusaurus-plugin-fathom')],
  themeConfig: {
    fathomAnalytics: {
      siteId: 'MY_FATHOM_CODE',
    },
  },
};
```

Note: tracking is enabled only on production mode
