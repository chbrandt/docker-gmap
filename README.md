# GMAP data publishing services

We assemble here the services for publishing data, in particular in the
view of GMAP.

Use Docker and docker-compose to run the services:
```bash
% docker-compose up
```

The following services are defined:
* `data-fileserver` (`PORT_DATA: 80`)
* `geoserver` (`PORT_GEOSERVER: 8080`)
* `jupyter` (`PORT_JUPYTER: 8000`)
* `maps-viewer` (`PORT_MAPS: 3000`)
* `data-submit` (`80: 5000`)

The default ports (indicated above) can be changed through docker-compose'
`.env` file.
