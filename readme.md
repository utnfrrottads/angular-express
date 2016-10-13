# angular-express
Yeoman generated angular fullstack variation with mocha, chai sinon and coverage.
As an example of an angular course.

# Installation
install git https://git-scm.com/downloads

## For Linux
Install nvm (Node Version Manager)
https://github.com/creationix/nvm

````
nvm install 6
````
then before running the app:
````
nvm use 6
````

## For Windows
You can use:
https://github.com/hakobera/nvmw
and then
````
nvm install 6
````
the before runn ing the app:
````
nvm use 6
````


I haven't tested with newer versions but it should work anyway.

## For both envs
````
npm install grunt-cli bower -g
git clone https://github.com/aotaduy/angular-example.git
cd angular-example
npm install
bower install
npm run update-webdriver
````

````
## To run the app
````
grunt serve
````

# Tests
### To run tests server and client
````
grunt test
````

# Code generation

You can use most of the generators listed in:
https://github.com/angular-fullstack/generator-angular-fullstack/tree/master/docs/generators



# Dev notes
private-bower
npm_lazy --config ~/npm_lazy.config.js
npm_lazy -p8123
npm install --registry http://localhost:8123
