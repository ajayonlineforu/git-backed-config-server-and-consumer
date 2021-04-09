Testing config-server
========================

1. http://localhost:8191/membership/prod or http://localhost:8191/membership/dev

same way we can test all other services for different profiles or environments.

All the configurations are stored in git https://github.com/ajayonlineforu/config-server-example


Testing config consumer
=========================

Start the consumer using profile - like 

java -jar consumer.jar -Dspring.profiles.active=dev/prod/qa
