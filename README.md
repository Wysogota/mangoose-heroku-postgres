# Initialization

Login to Heroku 
### `heroku login`

Create Heroku App 
### `heroku create your-app-name`

Push app to Heroku 
### `git push heroku master`

Create postgresql database on Heroku 
### `heroku addons:create heroku-postgresql:hobby-dev`

Set Production ENV
### `heroku config:set NODE_ENV=production`

# Usage

Run migrations
### `heroku run sequelize db:migrate` 

Run seeds
### `heroku run sequelize db:seed:all`

Reset database
### `heroku run sequelize db:migrate:undo:all` 