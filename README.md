# local-reverse-proxy-metrics

>  [traefik](https://github.com/containous/traefik) and [mkcert](https://github.com/FiloSottile/mkcert) based reverse proxy metrics

#### How to use?
* clone this repo
* create your certificates and update certificates.toml if neccesary (on your traefik)
* create docker networks and do up!

`$ git clone git@github.com:marcosdmyr/local-reverse-proxy-metrics.git`

`$ docker-compose up -d`

Open Grafana (visualize metrics) https://grafana.localhost with your web browser!

Open Portainer (visualize docker) https://portainer.localhost with your web browser!


#### Requirements
* docker
* docker-compose
* mkcert (optional)
* ensure localhost subdomains resolves to 127.0.0.1
* a running traefik on your machine

#### TODO
- Check some cpu metrics issues
