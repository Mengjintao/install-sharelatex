# install-sharelatex

Script to install ShareLateX on Ubuntu 16.04 LTS

# The ./reinstall.sh and ./uninstall.sh scripts remove ALL DOCKER CONTAINERS AND ALL VOLUMES! DO NOT USE IF YOU HAVE OTHER DOCKER CONTAINERS RUNNING.

Grant a user for sharelatex.

docker exec sharelatex /bin/bash -c "cd /var/www/sharelatex; grunt user:create-admin --email my@email.address" 
