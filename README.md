# Shopify Starterkit

[![Release](https://img.shields.io/github/release/quentin-f451/shopify-starterkit.svg)](https://github.com/quentin-f451/shopify-starterkit/releases)

This repo is my own starterkit for Shopify projects. It works with Webpack and allows to work with SCSS and ES6.

## Installation

1. In Terminal, go to your production folder:

```
cd path/to/my/folder
```

2. Clone this repository with the submodules

```
git clone https://github.com/quentin-f451/shopify-starterkit NAME-OF-MY-FOLDER
cd NAME-OF-MY-FOLDER
git clone --depth=1 https://github.com/quentin-f451/scss-starterkit.git src/scss
rm -rf ./src/scss/.git
```

3. Install Shopify Theme Kit

```
cd www
theme new --password=PASSWORD --store=NAME.myshopify.com --name=NAME
cd ..
```

4. Install dependencies with npm

```
npm install
```

5. Run `npm run start` and open another tab on the same folder. Run `theme watch` now and start coding.

6. At the end of your coding process, you can run the `npm run build` command.
