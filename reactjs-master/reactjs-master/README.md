
## Prerequisite
* Nodejs v6+
* yarnpkg (optional)


## Getting Started
```sh
git clone  https://github.com/sree0928/author-app.git

cd reactjs-crud-boilerplate

yarn install
    or
npm install

yarn start
    or
    
npm start
```

Open [http://localhost:3000](http://localhost:3000)<br>


## Libraries used
* ReactJs
* Redux
* create-react-app
* React Router 4
* Bootstrap 4
* redux-form
* React Boostrap Table
* Babel
* ESLint
* Test Runner: Jest
* Test Assertion: Jest
* Test Helper Library: Enzyme
* Test Headless DOM: JSDOM
* react-addons-test-utils: needed by Enzyme
* Mock API Data: hand rolled
* toastr
* jquery (needed by toastr and bootstrap 4)
* lodash
* Font Awesome: because Bootstrap 4 no longer suppies glyphicons
* Tether
* jquery
* thunk testing: nock (for mocking http calls), and redux-mock-store
* code coverage: Jest & coveralls


## Non create-react-app version
It's located in the branch **non-create-react-app**.
It uses hand crafted `Webpack 2`

```sh
git clone  https://github.com/sree0928/author-app.git

cd reactjs-crud-boilerplate

git checkout -b non-create-react-app origin/non-create-react-app

yarn install

yarn start
```


