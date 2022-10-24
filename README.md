# Multi Stage Docker build 
`Dockerfile` contains various stages which are tagged by a name using `as`.

## Commands used
- `docker build . -t multi-stage-example:v1` - Build image
- `docker run app-demo:v1 -p 8080:8080` - Run image