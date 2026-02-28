# Bsides Seattle 2026 - Demo Node.js App

## Demo App Endpoints

* `/ping?url=domain_to_ping`
* `/services?name=service_name_to_check`

## Build Demo App Container

`docker build -t mintoolkit/bsides-seattle-demo-app:latest .`

## Run Original Demo App Container

`docker run -it --rm -p 1300:1300 --name bsides --init mintoolkit/bsides-seattle-demo-app:latest`

