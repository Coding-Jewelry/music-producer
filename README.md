BEAT THREAD [![Circle CI](https://circleci.com/gh/BeatThread/beat-thread.svg?style=svg&circle-token=26614b014f5eeb27ae7accf9d6e2e03c2c675828)](https://circleci.com/gh/BeatThread/beat-thread)

Requirements

* Redis Server
* PostgreSQL

Setup

* git clone git@github.com:BeatThread/beat-thread.git
* cd beat-thread
* bundle install
* brew install imagemagick && brew install ffmpeg
* brew install memcached
* cp config/database.yml.example config/database.yml
* cp config/secrets.yml.example config/secrets.yml
* rake db:create db:migrate
* rake db:seed


Run in Development

* $ rails s
* $ redis-server
