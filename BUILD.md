# Requirements to build rust code
sudo apt-get install pkg-config libssl-dev

# Postgresql 
## install:
sudo apt install postgresql postgresql-contrib libpq-dev

## Use user:
sudo -i -u postgres
sudo -u postgres psql

## Start:
service postgresql start

## Create db user:
sudo -i -u postgres

createuser --interactive //user sam, superuser yes
createdb auth0_demo

# Diesel
cargo install diesel_cli --no-default-features --features postgres