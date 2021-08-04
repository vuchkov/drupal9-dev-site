# Drupal9 Dev Site

## Resources
- Local Dev environment - https://github.com/wodby/docker4drupal
- Drupal core 9.2.x
- Composer
- Git

## Install
- Add the following row in your `/etc/hosts` file:
```console
127.0.0.1	drupal9.localhost
```
- Open the local dev site on `http://drupal9.localhost:8000`.
- Admin UI user: admin/admin or generate a new one with `drush uli`.
- Use the DB backup from `.mysql` folder and add it in `.docker/.env`.
- The project uses "Configuration management".
