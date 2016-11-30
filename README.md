### Node.js / Express / PostgreSQL (Mongoose) starter kit

I created this simple starter kit 
to get started working on simple Node.js API project quickly

* [Node.js](https://nodejs.org/en/)
* [PostgreSQL](https://www.postgresql.org/)
* [Sequelize](http://docs.sequelizejs.com/en/v3/)
* [Sequelize-CLI](https://github.com/sequelize/cli)
* [JSON Web Token](https://jwt.io/)

**Hosting**

* [Heroku](https://www.heroku.com/)

**Testing**

* [Mocha](https://mochajs.org/)
* [Chai](http://chaijs.com/)
* [Supertest](https://github.com/visionmedia/supertest)


### Features

* [X] Linting (Airbnb)
* [X] Authentication with JSON Web Token
* [X] Username, Email, Password validations 
* [X] User signup, signin
* [X] API and Unit testing
* [X] Easily deployable to Heroku (Procfile)

### To run locally

Make sure to install and run PostgreSQL first.
```
brew update
brew install postgres
createdb npas-dev
```

Clone the repo and run the app
```
git clone git@github.com:yhagio/node-postgres-api-starter.git nd
cd nd
npm i 
npm run start
```

### To run test

```
npm run test
```

and in another tab
```
npm run test:only
```

### To deploy on Heroku
```
heroku login
heroku create
git push heroku master
```


#### Side Note

With `sequelize-cli`
```
./node_modules/.bin/sequelize init
```
will create model setup and edit `./config/config.json` for your database.
