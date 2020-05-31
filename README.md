# no-food-left-behind-server

### If you have postgres installed and want to run it locally:

#### Go into the .env file and edit postgres settings to your own environment

##### -ie: change `PGUSER: ''` to your postgres user role & password if you've set one

##### -(if password, see commented connection string in database/index.js and set up .env accordingly)

#### Start localhost server

##### -run `npm start` in the repo directory

#### Start local postgres server

##### - `pg_ctl -D /usr/local/var/postgres start`

#### Run the database model

##### -run `i\ database/models.sql` in the repo directory
