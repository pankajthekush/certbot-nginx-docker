* How to use
 - Edit nginx/conf/defautl.conf with your domains
 - run : docker-compose up
 - Open other terminal and run : 
		docker-compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ -d dhcx.datables.ai -d ei.datables.ai
		docker-compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ -d ei.datables.ai
 - replace those domains with your domain

more help: https://mindsers.blog/post/https-using-nginx-certbot-docker/
