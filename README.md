# Docker build script for SpiderFoot
This Dockerfile has been adopted from the official [SpiderFoot repo](https://github.com/smicallef/spiderfoot/blob/master/Dockerfile)
and adds support persistence of the database.

## To build
Execute:
```
docker build -t spiderfoot .
```

## To run
Execute:
```
docker run -it -p 8080:8080 -v /path/to/data/folder:/data spiderfoot
```
