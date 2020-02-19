# Configure mocha and chai

## Getting started:
1. npm install --save-dev mocha
2. npm install --save=dev chai

### `npm test`
Launches the test

configure test with "node node_modules/mocha/bin/mocha tests" (tests is the directory contains test)

#### Run mocha in cmd
`on specific tests`

node node_modules/mocha/bin/mocha -g (testname_mentioned_in_it_block) tests(test directory)

`on specific directory`

node node_modules/mocha/bin/mocha tests(test directory)

`on specific file`

node node_modules/mocha/bin/mocha tests/mocha_test1.js(test directory/specificfile.js)

`on matching file`

node node_modules/mocha/bin/mocha tests/*1.js(test directory/pattern_to_identify.js)

#### Run mocha is vscode
Install extension - https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-mocha-test-adapter

### `configure custom test directory in windows:`
File | preferences | settings or (ctrl + ,)
under settings.json or workspace_settings add custom directory to execute test is vs code with below settings
{
    "mochaExplorer.files":"tests/**/*.js"
}


