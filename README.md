# Docker Spring Eureka Zuul - Demo App
Example application that contains multiple a springboot service that registers with a Eureka Registry.  
Zuul then serves the requests to these services based on the provided app name

## Quick Start
* Build each service
* Deploy services using the example stack file.
* Eureka dashboard can be reached at: `http://localhost:8761/`
* Each service can be reached through the Zuul gateway at: `http://localhost:9090/${APP_NAME}`