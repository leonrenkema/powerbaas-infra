# Setup

Voordat deze docker-compose gebruikt kan worden moeten Docker en docker-compose geïnstalleerd zijn. 

Docker installeren kan redelijk eenvoudig met het volgende commando:

```
curl -fsSL https://get.docker.com | sh
```

Het kan handig zijn om de gebruiker toe te voegen aan de `docker` groep. Dan hoeft er geen sudo gebruikt te worden bij docker commando's.

https://docs.docker.com/compose/install/#install-compose

# Opstarten 

```
docker-compose up -d
```

Grafana is bereikbaar op http://raspberrypi:3000

# Stoppen

```
docker-compose stop
```
