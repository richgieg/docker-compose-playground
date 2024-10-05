# docker-compose-playground

Contains compose.yml files for quickly trying various CMS platforms with Docker Compose.

Once an app is started with one of the following commands, it will be available at http://localhost:8080
and the database will be available for inspection on localhost:3306.

### Drupal
```
docker compose -f ./drupal/compose.yml up
```

### Joomla
```
docker compose -f ./joomla/compose.yml up
```

### WordPress
```
docker compose -f ./wordpress/compose.yml up
```
