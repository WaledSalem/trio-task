# Trio-task

- Clone down this repository.
- Containerise the Flask application in the flask-app directory.
- Bind mount the nginx.conf file onto the NGINX container and run the NGINX container and the Flask app together.
- Use a bind mount to mount the SQL dump file CreateTable.sql in the directory db onto the MySQL 5.7 container (details on where it should be mounted can be found in the Dockerfile)
- Run curl localhost or navigate to your machine's network location in your browser.
- Remember that your containers will have to be on the same network.