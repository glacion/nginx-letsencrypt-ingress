# Docker Ingress

This is an attempt to provide functionality similar to kubernetes' ingress + cert-manager. Useful for more simple environments

## Usage

- Make sure your domain and subdomains are pointing at the IP address of your machine.

- Clone this repository on your server.

- Run `docker-compose.yml`

## Example

The [Example compose file](./example/docker-compose.yml) demonstrates how to deploy an nginx container using this.

## Acknowledgements

[Nginx Proxy](https://github.com/nginx-proxy/nginx-proxy)  
[Letsencrypt Companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion)
