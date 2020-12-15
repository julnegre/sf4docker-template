# to build : 
docker-compose build
then : 
docker-compose up -d

# to stop :
docker-compose stop

# building command : 
- ``docker-compose exec php composer install``
- ``docker-compose exec php php bin/console doctrine:schema:create``
- ``docker-compose exec php php bin/console doctrine:fixtures:load``
- ``docker-compose exec php php bin/console assets:install –symlink public/``
