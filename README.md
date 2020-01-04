# VR-workshop

## Run https
Install the server

`npm install -g http-server`

Generate certs

`openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem`

Run http-server with https

`http-server -S -C cert.pem -o`