Custom Docker Compose template for [Minio](https://www.minio.io/).
This template is meant to be used with [nginx-proxy](https://github.com/jwilder/nginx-proxy). Use [this template](https://github.com/rann91/docker-compose-nginx-proxy) to setup nginx proxy quickly.

## Usage
Copy default .env file and configure variables. Then simply run docker-compose:
```
docker-compose up -d
```

To enable SSL, run the following command:
```
docker-compose up -f docker-compose.yml -f docker-compose.prod.yml -d
```

That's it!
