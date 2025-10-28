# superset - dok

Starting with:
git clone https://github.com/apache/superset

Followed by:

## Enter the repository you just cloned
$ cd superset

## Set the repo to the state associated with the latest official version
$ git checkout tags/5.0.0

## Fire up Superset using Docker Compose
$ docker compose -f docker-compose-image-tag.yml up



## Restart:
Open Docker first by:
open -a Docker

Start Superset again with:
docker compose -f docker-compose-image-tag.yml up




Setup a local postgresql installation:
## Homebrew installieren (falls noch nicht geschehen)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## PostgreSQL installieren
brew install postgresql

## PostgreSQL starten
brew services start postgresql
