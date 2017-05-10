# code-cata
Code kata exercise environment

Run `docker-compose up`

####Install composer
`docker-compose -f docker-compose.yml run --rm cata-php composer install`

####Run phpSpec
 
`docker-compose -f docker-compose.yml run --rm cata-php php vendor\bin\phpspec`

####Run phpunit
 
`docker-compose -f docker-compose.yml run --rm cata-php php vendor\bin\phpunit -c phpunit.xml`
