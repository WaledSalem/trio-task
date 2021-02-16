# Trio-task

This exercise gets you to run a Flask application container, a MySQL container and an NGINX container in a network.

* Containerise the MySQL database and the Flask application in this repository
    - You will have to write the Dockerfile to build the images - a Dockerfile template has been provided for both images.
    - Look up the MySQL 5.7 image documentation on Docker Hub to learn how to configure the database.
* Create a network and connect the Flask application container, database container and an NGINX container to it.
    - Remember to bind mount the nginx.conf file as shown in the tutorial above
* Navigate to your application either through your browser or on the command line with curl localhost.