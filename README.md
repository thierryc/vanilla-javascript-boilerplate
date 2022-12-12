# Vanilla Javascript Boilerplate

"Simplicity is the ultimate sophistication."

This repository contains my work in progress boilerplate.

This is a modern and simple boilerplate for Vanilla JavaScript projects. It is based on the latest version of ECMAScript (ES2020) and provides support for ES6 and ES7 features out of the box.

## Features

- Uses Parcel as the build system, which makes it easy to get started and produces small, efficient bundles
- Includes a set of polyfills to ensure that your code works in older browsers
- Supports CSS modules, which allows you to write modular and reusable CSS code
- Comes with a development server that automatically reloads the page when you make changes to your code
- Includes a linter and formatter to help you write clean, consistent code

## Getting Started

Clone the repository and install the dependencies:

### HTTPS clone

```bash
git clone https://github.com/thierryc/vanilla-javascript-boilerplate.git
cd vanilla-javascript-boilerplate
npm install
```

### Github Cli

Use Github official CLI. [Learn more](https://cli.github.com).

```bash
gh repo clone thierryc/vanilla-javascript-boilerplate
cd vanilla-javascript-boilerplate
npm install
```

### Rename the project.

Replace "vanilla-javascript-boilerplate" by your own name.

Run the development server:

```bash
npm run dev
```

Open [http://localhost:1234](http://localhost:1234) in your browser to view the project.
Edit the src/index.js file to start building your project.
Building for Production

To build the project for production, run the following command:

```bash
npm run build
```

This will generate a production-ready bundle in the dist directory.

## Links and documentation

- https://developer.mozilla.org/en-US/
- https://vanillajstoolkit.com
- https://javascript.info
- https://web.dev/learn/pwa/


## TODO

- [X] Setup Parcel
- [ ] CLI documentation
- [ ] Manifest documentation
- [ ] Nested post CSS config and documentation
- [ ] Webworker for PWA support
- [ ] Setup a app icons & favico workflow and link a Figma file to edit it.
- [ ] Delpoy documentation for Surge
- [ ] Delpoy documentation for Vercel
- [ ] Delpoy documentation in general
- [ ] tests for JavaScript

## browserslist

```json
"browserslist": "> 0.2%, last 2 versions, not dead",
```

https://browserslist.dev/?q=PiAwLjIlLCBsYXN0IDIgdmVyc2lvbnMsIG5vdCBkZWFk

## License

This project is licensed under the MIT License - see the LICENSE file for details.

