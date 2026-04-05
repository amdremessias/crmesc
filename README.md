# crmesc
CRM_Basico


docker-compose down -v --remove-orphans
docker-compose up -d
docker exec -it espocrm chown -R www-data:www-data /var/www/html
