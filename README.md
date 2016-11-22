Docker, PHP & nginx Development Environment
=================================


### Install
Creates linked php and nginx containers and starts them up using `docker-compose`

```
$ npm install
```

# Utilities

#### Start
Starts the docker environment
```
$ npm run docker:start
```

#### Stop
Stops the docker environment
```
$ npm run docker:stop
```

#### Clean Up
Stops the docker environment, removes the containers and removes the docker images
```
$ npm run docker:nuke
```

#### Error Logging
```
$ npm run docker:logs
```

# Configuration

| Service Name | Description | Location | Documentation |
|--------------|----------|--------------------| ----------|