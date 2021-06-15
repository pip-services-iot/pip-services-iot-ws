# <img src="https://github.com/pip-services/pip-services/raw/master/design/Logo.png" alt="Pip.Services Logo" style="max-width:30%"> <br/> Workspace for IoT Pip.Services

This is a workspace for [IoT Pip.Services](https://github.com/pip-services-iot) 
implemented in 5 different languages: .NET, Java, Node.js, Go and Python.

The workspace enables build, test, and release across the following projects:

- **pip-services-devenv** - dockerized infrastructure services for development and testing
- **pip-services-beacons-node** - Beacons microservice in Node.js
- **pip-clients-beacons-node** - Client to Beacons microservice in Node.js
- **pip-services-positions-node** - Object positions microservice in Node.js
- **pip-clients-positions-node** - Client to Positions microservice in Node.js
- **pip-services-routes-node** - Object routes microservice in Node.js
- **pip-clients-routes-node** - Client to Routes microservice in Node.js
- **pip-services-routeanalysis-node** - Route Analysis microservice in Node.js
- **pip-clients-routeanalysis-node** - Client to Route Analysis microservice in Node.js
- **pip-services-transducerdata-node** - Transducer data microservice in Node.js
- **pip-clients-transducerdata-node** - Client to Transducer data microservice in Node.js
- **pip-services-cameras-node** - Cameras microservice in Node.js
- **pip-clients-cameras-node** - Client to cameras microservice in Node.js

## Installation

- Clone this workspace to local disk
```bash
> git clone https://github.com/pip-services-infra/pip-services-infra-ws.git
```

- Got to the workspace folder and clone component repositories
```bash
> ./checkout.sh
```

## Acknowledgements

The Infrastructure Pip.Services are created and maintained by **Sergey Seroukhov**
