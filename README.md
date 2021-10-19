***RUN MYSQL and WORDPRESS via Docker compose.***

This guide walks through the deployment of a WordPress container and another MySQL container that WordPress will use to store its data. Docker Compose will facilitate the networking between them.

WordPress is a free and open source blogging tool and a content management system (CMS) based on PHP and MySQL, which runs on a web hosting service.

**Steps to proceed:**

1. Make a directory for wordpress. Eg: mkdir mywordpress and cd mywordpress/

2. Write a Docker-compose.yml file

3. *docker-compose up -d* (Detached mode: Run containers in the background, print new container names)

4. The Docker containers will take a minute or two to start up WordPress and MySQL.

5. Afterwards, open the wordpress web application through http://localhost:8080/wordpress/ and the app starts.

6. We can optionally set up a domain for our WordPress site.

7. To stop our WordPress application: *docker-compose down*

Note: When a Docker container is stopped, it is also deleted; this is how Docker is designed to work. However, your WordPress files and data will be preserved, as the docker-compose.yml file was configured to create persistent named volumes for that data.

***RUN DRUPAL and POSTGRES via Docker compose.***

This guide walks through the deployment of a Drupal container and another PostgreSQL container that Drupal will use to store its data. Docker Compose will facilitate the networking between them.

Drupal is an open source content management platform powering millions of websites and applications. It is used as a back-end framework for at least 2.1% of all Web sites worldwide ranging from personal blogs to corporate, political, and government sites including WhiteHouse.gov and data.gov.uk. It is also used for knowledge management and business collaboration.

**Steps to proceed:**

Same steps from above till step 4 has to be followed.

5. Afterwards, open the Drupal web application through http://localhost:8080/ and the app starts.

6. On the Set up database page, select PostgreSQL as the Database type and enter the following values:

Database name: postgres

Database username: postgres

Database password: The password you set in the docker-compose.yml file

Host (under Advanced Options): postgres

7. Complete the other screens in the setup guide. When creating Drupal user, be sure to enter a password that is different from PostgreSQL password.

8. To stop our Drupal application: *docker-compose down*

**OUTPUT**
