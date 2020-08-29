Development Workflow
====================
* Development workflow process involves
    1. Develop
    2. Test
    3. Deploy

 Travis CI 
-----------
*Travis CI* is a continues integration provider.  
It will pull down the source code and run tests and then merge changes to master branch.  
Once the tests are successful it will deploy to AWS Hosting.


Develop
-------
*Docker Container* is used as local development environment.  

Client
------
### Install React App
```sh
npm install -g create-react-app
create-react-app frontend
```
OR
```sh
  # Create a new app Frontend
  npx create-react-app frontend

  # Starts the development server.
  yarn start

  # Bundles the app into static files for production.
  yarn build

  # Starts the test runner.
  yarn test
```
### uninstall the create-react-app globally
```sh
  npm uninstall -g create-react-app
```
