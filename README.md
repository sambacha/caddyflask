# CaddyFlask Docker Server

> Basic template for Caddy-based Python Flask Server


## Usage

### Local

1. Generate local HTTPS certificates

```
mkcert -install flask.localhost
```

2. Spin up application

```
docker-compose -f local.yml up --build
```

### Production

1. Have a DNS record pointing at the server you run this on

2. Spin up application

```
docker-compose -f production up --build
```

## License 

ISC 
