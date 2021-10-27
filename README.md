# Nextcloud docker
## Configs
### Docker secrets
Installation uses some secrets located under `./private` directory:
- nextcloud_admin_user: nextcloud admin username.
- nextcloud_admin_password: nextcloud admin password.
- postgres_db: name of postgresql database.
- postgres_user: postgresql database user.
- postgres_password: postgresql database user password.

### Nextcloud
Config is located under `"$NC_PATH/config/config.php"`.
After first-run you need to change (or add)
`'overwrite.cli.url' => 'https://shuta4.com/nextcloud',`.
