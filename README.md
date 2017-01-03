# xAPI-testbed
This is a set of Docker containers you can use to test xAPI. They are orchestrated with a Docker-compose file. 

Components:
*  Docker-compose.yml
*  WordPress site with plugins: H5P, H5P-xAPI
  * DB for WordPress (MariaDB)
  * http://wp-cli.org/
*  LRS (LearningLocker)
  *  MongoDB
  
Third-party:
*  https://github.com/hongymagic/learninglocker/tree/1.12.1-http
*  https://hub.docker.com/_/wordpress/
  *  (https://github.com/docker-library/wordpress/tree/master/apache)
