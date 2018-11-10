# nginx-honey-alpine
Dockerized version of nginx as reverse proxy for honeypot rspamd ui, based on Alpine Linux

## Usage
NOTICE: This image is built for the unique scope to serve ad reverse proxy on a docker stack with an Rspamd container named rspamd and listening on port 11334. MORE DETAILS COMING IN FUTURE

You can run this container with this command:  
`docker run -d --name nginx-honey-alpine -p 80:80 neomediatech/nginx-honey-alpine`  


