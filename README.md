# docker_rails

```
cd docker_rails
docker-compose run web rails new . --force --database=postgresql 
docker-compose build
docker-compose run web rake db:create
docker-compose run web rake db:migrate
docker-compose up
```

