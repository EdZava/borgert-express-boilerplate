

# Boilerplate Node Express 


#### Install
> npm install

#### ENV
> cp .env-example .env

#### Configure .env
> MONGO_DB=mongodb://localhost:27017/mongo_db
> APP_TOKEN=MyTokenForSession

#### Development (With nodemon watch .js and .twig)
> npm run dev

> http://localhost:3000

#### Eslint
> npm run eslint

#### Packages
- View engine: twig
- Security: helmet
- Flash: express-flash
- Session: express-session
- Encrypt: bcryptjs
- Modules: express-load
- Database: MongoDB
    - ORM: Mongoose
    - Mongoose Paginate
    - Mongoose Validator
- Logs: winston + winston-daily-rotate-file
- Nodemon
- CSS: stylus
- Eslint + Husky
