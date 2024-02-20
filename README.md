# MDX2JSON-docker
The OEX package just uses a modest IRIS instance in Docker     
It merges IPM package of MDX2JSON with some demo data    
It is built using the small [Mini-Docker-Template](https://github.com/r-cemper/mini-docker)    
### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory    
```
$ git clone https://github.com/rcemper/MDX2JSON_docker.git
```
To build and start the container run:  
```
$ docker compose up -d && docker compose logs -f
```
To open IRIS Terminal do:
```
$ docker-compose exec iris iris session iris
USER>
```
or using **WebTerminal**
```
http://localhost:42773/terminal/
```
IRIS System Management Portal
```
http://localhost:42773/csp/sys/UtilHome.csp
```
## What does it do
Presents OEX package [MDX2JSON](https://github.com/intersystems-community/Cache-MDX2JSON) using actiual IPM package  
All user documentation is found in the original repo      
