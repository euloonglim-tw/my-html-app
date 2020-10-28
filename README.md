### Introduction

Simple html app with scss used to test _Impact X_ styles and web components.

### Prerequisites

- Node 14 or higher
- Yarn 1.22.4 or higher

### Installation

1. Clone the repo using https: 

    `git clone https://github.com/euloonglim-tw/my-html-app.git`

2. Change directory to the `my-html-app` folder.


3. Check that node is installed (if not, [install node](https://nodejs.org/en/download/package-manager/)):

    `node -v`

4. Check that yarn is installed (if not, [install yarn](https://classic.yarnpkg.com/en/docs/install/)):

    `yarn --version`

5. Run `yarn` to update the packages.


6. Run the `sass` script in the `package.json` file (This uses `node-sass` to compile the `main.scss` file into the `main.css` file):

    `yarn sass`

    This should give a `Rendering Complete` message. Don't make css changes to the style in the `main.css` file, use the `main.scss` file (remember to `yarn sass` to apply the changes).

7. Run the server:

    `yarn server`

8. You can now follow the _Impact X_ installation steps for [Design Tokens](https://tw-impact-x.thoughtworks-labs.net/#/Using%20Impact%20X/Installation/Design%20Tokens), [Styles](https://tw-impact-x.thoughtworks-labs.net/#/Using%20Impact%20X/Installation/Styles) and [Web Components](https://tw-impact-x.thoughtworks-labs.net/#/Using%20Impact%20X/Installation/React%20%26%20Web%20Components).

> Note: If you are using `zsh`, you will need to update imports to the relative path, e.g. `@import '~@impact-x/tokens';` to `@import '../node_modules/@impact-x/tokens';`.