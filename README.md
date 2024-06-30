# crow-stylelint-config [![npm version](https://img.shields.io/npm/v/crow-stylelint-config?logo=npm&logoColor=fff)](https://www.npmjs.com/package/crow-stylelint-config) [![CI Status](https://img.shields.io/github/actions/workflow/status/ecossistemadev/crow-stylelint-config/test.yml?branch=main&label=CI&logo=github)](https://github.com/ecossistemadev/crow-stylelint-config/actions/workflows/test.yml?query=workflow%3ATests+branch%3Amain)

> An opinionated Stylelint config used by Crow across our projects.

## Installation

```bash
npm install crow-stylelint-config --save-dev
# Or with yarn:
yarn add crow-stylelint-config --dev
```

## Usage

We provide a single config that covers both CSS and SCSS. It will automatically apply SCSS rules to files ending in `.scss`.

You simply have to extend this config in your Stylelint config:

```json
{
  "extends": "crow-stylelint-config"
}
```

To see the included rules, please check [index.js](index.js).

## License

Released under the [MIT License](LICENSE).
