## Docker Alpine for Laravel Framework

This is my custom image to run Laravel Framework using Docker and Alpine Linux  
I have separated it to 3 container:  
1. `app` container to run and execute `php` command/script  
2. `web` container to run `nginx` server  
3. `database` using `mysql:5.7` image

Feel free to use or modify this.

note: some of these images are created and modified from [this repo](https://github.com/nielsvandoorn/docker-alpine-laravel "Docker Alpine Laravel")
