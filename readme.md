## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Shopify Credentials

Copy the `config.yml.default` local and update the `password` fields. Create a Theme Kit Access password for yourself [Theme Kit Access](https://nydj-apparel.myshopify.com/admin/apps/theme-kit-access/).

```
cp config.yml.default config.yml
```

### Prerequisites

What things you need to install the software and how to install them

```
https://nodejs.org/en/
https://shopify.github.io/themekit/
```

### Installing

```
yarn install
```

### Development

Keep gulp / themekit running during development.

```
yarn watch
```
