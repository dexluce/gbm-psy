## About
This code is under ©copyright license. It is accessible for documentation and learning purpose only.

## Installation
This repo is a dev repo. It is there to offer a full stack dev environment.
If you want to try it, you'll need to clone the [frontend](https://github.com/dexluce/gbm-psy_frontend) and [backend](https://github.com/dexluce/gbm-psy_backend).<br/>
Once that's done, you can build and start the project:
```
docker-compose -f docker-compose.yml -f docker-compose.minio.yml -f docker-compose.jitsi.yml -f docker-compose.frontend.yml -f docker-compose.db.yml -f docker-compose.backend.yml up
```

## Dependency
You'll need Docker and docker-compose to run it.

## Disclaimer
This project is code by one person only, and specifications are changing on a weekly basis.
