Docker, PHP & nginx Development Environment
=================================


### Install
Creates linked php and nginx containers and starts them up using `docker-compose`

```
$ npm install
```

# Docker Utilities

#### docker:start
Starts the docker environment
```
$ npm run docker:start
```

#### docker:stop
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

# Opencart Utilities

#### opencart:install
```
$ npm run opencart:install
```


# Configuration

| Service Name | Description | Location | Documentation |
|--------------|----------|--------------------| ----------|