# Setup

docker compose up -d nginx

docker -compose run --rm certbot certonly --webroot --webroot-path /var/www/certbot/ -d ivanlogvynenko.ddns.net
