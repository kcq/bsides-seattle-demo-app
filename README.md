# Bsides Seattle 2026 - Demo Node.js App

## Demo App Endpoints

* `/ping?url=domain_to_ping`
* `/services?name=service_name_to_check`

## Build Demo App Container

`docker build -t mintoolkit/bsides-seattle-demo-app:latest .`

## Run Original Demo App Container

`docker run -it --rm -p 1300:1300 --name bsides --init mintoolkit/bsides-seattle-demo-app:latest`

## Explore Demo App Container

https://ima.ge.cx/mintoolkit/bsides-seattle-demo-app:latest

## Explore Obfuscated Demo App Container

https://ima.ge.cx/mintoolkit/bsides-seattle-demo-app:latest.obfuscated

## Explore Obfuscated Demo App Container (with Empty Package Names)

https://ima.ge.cx/mintoolkit/bsides-seattle-demo-app:latest.obfuscated.names-empty

## Explore Obfuscated Demo App Container (with Mutated Package Names)

https://ima.ge.cx/mintoolkit/bsides-seattle-demo-app:latest.obfuscated.names-random

