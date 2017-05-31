Your goal is to visit the default welcome page of an NGINX
inside a docker container, managed by docker-compose,
and visit the standard welcome page in your browser.

Assuming you've already installed Docker-compose, complete this koan by…

1. Open the `docker-compose.yml`.
1. Comment in the two commented lines, to forward port `80` in the container to your hosts' `8080`.
1. Run the service with `docker-compose up`.
1. Open http://localhost:8080/ in your browser. You should see the NGINX welcome page.

TADA!

1. Stop NGINX with `CTRL-C`.
1. Start the system (well, it's only the NGINX container) with `docker-compose start`.
1. Open http://localhost:8080/ in your browser. You should see the NGINX welcome page again.
1. Run `docker-compose ps`. You'll see that the container is running in the background.
1. Run `docker ps` (not docker-compose), and compare the output.
1. Stop the container with `docker-compose stop`.

Cleanup:

1. `docker-compose down`
