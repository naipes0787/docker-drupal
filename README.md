# Drupal bootstrap
Use `docker-compose up` to start the necessaries containers to use Drupal with PostgreSQL. After started you can go to `localhost:8080` to configure Drupal.

## Database configuration
The basic database configuration is this one:
- Database name: `postgres`
- Database user: `postgres`
- Database password: `example`

In the `ADVANCE OPTIONS` we have to set the host which in this case is not localhost, but the name of our postgres service: `postgres`
