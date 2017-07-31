# Docker Setup with PHP, MariaDB, Redis and Caddy webserver
The whole setup is controlled through the compose file

# Issue
At version 6.4.0 directus is missing some columns for the `directus_files` table,
these being `url`, `thumbnail_url`, `old_thumbnail_url` and `html`