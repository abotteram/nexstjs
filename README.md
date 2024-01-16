Install https://github.com/FiloSottile/mkcert

Execute the following commands
```
mkcert -key-file certs/key.pem -cert-file certs/cert.pem localhost
mkcert -install
```

To start the dev environment run
```
docker compose up -d --build
```