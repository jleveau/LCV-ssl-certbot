# LCV-Event

# build with docker 
$ docker  build -t oursgroumy/lcv-ssl-certbot .

# create certificates
$  docker exec -it certbot bash
$  /scripts/certbot-auto certonly --webroot -w /webroots/le-cerf-vert.ovh -d <domain-names>
you can repeat -d for multiple domains