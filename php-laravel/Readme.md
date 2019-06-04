# Clone the laravel app and move all files in this folder to the cloned repository

## Setup

```sh
$ git clone https://github.com/laravel/laravel.git laravel-app
$ mv ./  /path/to/laravel-app/
```

## Install Dependencies

```sh
docker run --rm -v $(pwd):/app composer install
```


[Reference link](https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose)
