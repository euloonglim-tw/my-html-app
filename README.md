### Introduction

Simple html app with scss used to test _Impact-X_ styles and web components.

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