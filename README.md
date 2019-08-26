#  Stratus Meridian Dev Portal Docker Implementation

Hi! We wanted to build a quick docker implementation to containerize developer portal. Please feel free to fork and make it your own or add your contributions!

# Setup

 1. Make sure you setup Docker first. https://docs.docker.com/install/ 
 2. `cd apache-debian-mariadb` (More stack versions to come) 
 3. Run  `docker-compose up -d --build`
 4. Go to http://localhost:8080 and finish your setup. (If you're using this port already, change it to your desired port on docker-composer.yml

# Config
1. DB name -- 'apache-debian-mariadb_db_1'
2. DB username -- 'root' 
3. DB pass -- 'drupal_db_pass' 
(refer to docker-compose.yml)

## Questions & Issues ?

Please raise an issue ticket here. 
