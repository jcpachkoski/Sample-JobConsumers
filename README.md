# Job Consumer Sample

Use the `docker-compose.yml` file to startup RabbitMQ and Postgres, the service (container) will also start but Postgres will
error since the database is not yet created.  Stop the service container only, then restart it to create the database and
everything will be OK. Note that I added a data volume in the docker-compose.yml file for Postgres so if you ever stop all the containers and restart, things will still work.

Navigate to `https://localhost:5001/swagger` or `http://localhost:5000/swagger` to post a video to convert. Enjoy the show!
Determine why only the second one with http, above, works to get to swagger and not the first one with https???

Run docker-compose down, then delete all the containers and images from DockerDesktop and follow the above instructions, again, to start over.
