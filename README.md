# Welcome to No Food Left Behind

We are a group of individuals committed to helping people find the resources they need
to learn about eliminating food waste. When we waste food, we waste the resources to 
produce it, including land, water, energy. This project is geared towards the donors
and recipients in mind.

## Interested in contributing?
1. `git clone https://github.com/No-Crop-Left-Behind/no-food-left-behind-server.git`
2. `cd no-food-left-behind-server`

If you have postgres installed and want to run it locally:
#### To start localhost server:
1. Go into the .env file and edit postgres settings to your own environment
- ie: change `PGUSER: ''` to your postgres user role & password if you've set one
- (if password, see commented connection string in database/index.js and set up .env accordingly)
2. Change into a directory you would like to save this project
3. `npm install`
4. `npm start`

#### To start set up local postgres database:
1. `pg_ctl -D /usr/local/var/postgres start`
2. run `i\ database/models.sql` in the repo directory
