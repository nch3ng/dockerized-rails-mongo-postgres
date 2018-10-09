# dockerized-rails-mongo-postgres

Have docker & docker-compose installed

First time deploy:

```
docker-compose up -d
docker-compose run app rake db:setup
docker-compose run app rake db:migrate
```

Open browser:

http://localhost:3000