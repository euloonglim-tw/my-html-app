### Introduction

Simple html app with scss used to test _Impact-X_ styles and web components.

### Installation

1. Clone the repo using https: 

    `git clone https://github.com/euloonglim-tw/my-html-app.git`

2. Check that node is installed (if it is not installed, [install node](https://nodejs.org/en/download/package-manager/)):

    `node -v`

3. Check that yarn is installed (if not, [install yarn](https://classic.yarnpkg.com/en/docs/install/)):

    `yarn --version`

4. Start a new project (this creates/updates the package.json), keep pressing enter to choose the default options.

    `yarn init`

5. Install node-sass (needed for using sass, this creates a yarn.lock file and installs the node_modules).

    `yarn add node-sass`

6. Check the version of node-sass installed by using:

    `node-sass -v` or (depending on PATH status) `node_modules/.bin/node-sass -v`

7. Add live-server, this is used to create a local server for the app:

    `yarn add live-server`

8. Don't make changes to the style in the main.css file, use the main.scss file. You can now run the `sass` script from the package.json file to compile the main.scss file into the main.css file by the use of node-sass:

    `yarn sass`

    This should give a `Rendering Complete` message.

9. Run the server:

    `yarn server`