# Sample Rails Docker App

1. run `docker-compose up --build`

2. reset the database `docker-compose exec --user "$(id -u):$(id -g)" website rails db:reset`

3. run the migrations `docker-compose exec --user "$(id -u):$(id -g)" website rails db:migrate`

3. visit `localhost:3000`