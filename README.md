# DevEnvironmentDocker
include mysql / mongodb / adminer / redis / phpredisAdmin / elasticsearch

# Install Docker
 - Docker
 - Docker-compose

# To Up Container
 - docker-compose-up -d

# Change DB Auth
 - In docker-compose.yml
   - Mysql
   - environment:
       - MYSQL_ROOT_PASSWORD: whatyouwant
   - MongoDB
   - environment:
       -  MONGO_INITDB_ROOT_USERNAME: root
       -  MONGO_INITDB_ROOT_PASSWORD: whatyouwant

# Change Adminer Max Upload
 - Use uploads.ini to change

# Use
 - Mysql         
   - localhost:3306   root/123456 (default)
 - MongoDB       
   - localhost:27017  none        (default)
 - Adminer       
   - localhost:9100
 - Redis         
   - localhost:6379
 - phpRedisAdmin 
   - localhost:8081
 - Elasticsearch 
   - localhost:9200 / localhost:9300
