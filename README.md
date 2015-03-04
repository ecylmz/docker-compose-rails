#   Docker Compose Rails Example

```sh
$ docker-compose run web rails new . --force --database=postgresql --skip-bundle
$ docker-compose build
$ docker-compose up
$ docker-compose run web rake db:create
```
