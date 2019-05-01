# Deprecated 
This repository has been deprecated. Please find the latest code here: https://github.com/vaadin-component-factory/vcf-paginator

[![Build Status](https://travis-ci.org/vaadin/incubator-paginator.svg?branch=master)](https://travis-ci.org/vaadin/incubator-paginator)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# &lt;incubator-paginator&gt;

[Live Demo ↗](https://incubator.app.fi/incubator-breadcrumb-demo)

[&lt;incubator-paginator&gt;](https://vaadin.com/directory/component/vaadinincubator-paginator) is a Web Component providing an easy way to display a full functioning paginator on a webpage.

```html
  <incubator-paginator id="my-paginator" total-pages="15" current-page="3">
  </incubator-paginator>
```

[<img src="https://raw.githubusercontent.com/vaadin/incubator-paginator/master/screenshot.png" width="200" alt="Screenshot of incubator-paginator">](https://vaadin.com/directory/component/vaadinincubator-paginator)


## Installation

The Vaadin Incubator components are distributed as Bower packages.

### Polymer 2 and HTML Imports compatible version

Install `incubator-paginator`:

```sh
bower i vaadin/incubator-paginator --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/incubator-paginator/incubator-paginator.html">
```

## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/incubator-paginator.html`

  Unstyled component.

- `theme/lumo/incubator-paginator.html`

  Component with Lumo theme.

- `incubator-paginator.html`

  Alias for theme/lumo/incubator-paginator.html


## Running demos and tests in browser

1. Fork the `incubator-paginator` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `incubator-paginator` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/incubator-paginator/demo
  - http://127.0.0.1:8080/components/incubator-paginator/test


## Running tests from the command line

1. When in the `incubator-paginator` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin components team members


## License

Commercial Vaadin Add-on License version 3 (CVALv3). For license terms, see LICENSE.

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
