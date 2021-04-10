Testing config-server
========================

1. http://localhost:8191/membership/prod or http://localhost:8191/membership/dev

same way we can test all other services for different profiles or environments.

2. we can get properties file(.yml) file as well like below

http://localhost:8191/membership-prod.yml or http://localhost:8191/membership-prod.properties or http://localhost:8191/membership-prod.json

All the configurations are stored in git https://github.com/ajayonlineforu/config-server-example

3. we can pull configuration with the git commit has as well like below

http://localhost:8191/membership/prod/eba1268078e1f125d2cc104f4f970a14ce9cb01d

Testing config consumer
=========================

Start the consumer using profile - like 

java -jar consumer.jar -Dspring.profiles.active=dev/prod/qa
