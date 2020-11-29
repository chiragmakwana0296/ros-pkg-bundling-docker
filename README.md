# ROS Package Bundling Docker

## Description
This repository contains docker-comtainer to build ros debian packge using bloom-generate


## Requirements
- [Docker](https://docs.docker.com/engine/install/)
- [docker-compose](https://docs.docker.com/compose/install/) 
## Usage
### docker-compose
This command will bundle all the ros pacages contained in the source folder 'src'
```shell
docker-compose up --build ros-bloom
```
Generated artifacts will be stored in "Debian" directory in ros package

