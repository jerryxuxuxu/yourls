# yourls for docker

To run the docker container

mount your configuration file config.php to the container

~~~
docker run --name yourls -d -p 80:80 -v /your/config/dir:/app/user jerryxuxuxu/yourls
~~~
