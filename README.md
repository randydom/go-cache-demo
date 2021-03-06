# Server-side cache with Go

Read more about this at [https://goenning.net/2017/03/18/server-side-cache-go/](https://goenning.net/2017/03/18/server-side-cache-go/).

# How to use it

- Clone this repository
- Install glide (https://github.com/Masterminds/glide)
- Run `glide install` while on project root folder
- Run `make run-memory` or `make run-redis` to start the web application
- If you want to use redis, make sure you have a redis server running locally. If you don't start a new redis docker container by running `docker-compose up -d`
- Navigate to `http://localhost:8080`

# Demo application

You can see this application running live on [https://go-cache-demo.herokuapp.com/](https://go-cache-demo.herokuapp.com/)

Happy Coding! :)