>[[!NOTES]]
>We can use `{CONTAINER_NAME}` instead of `{CONTAINER_ID}`
```shell
# for showing images
docker images
# for showing running containers
docker ps
# for showing all containers
docker ps -a
# pull an image from registry (docker hub)

# tag -> version
docker pull {name}:{tag}
# Example
docker pull nginx:1.23
# Run an image (CREATE A NEW CONTAINER)
docker run {name}:tag

# Run an image (without interupting the terminal)
# Add flag -d (or --detach)
docker run -d {name}:{tag}

# We don't need to pull a docker img before running it, we can simply type docker run... then docker will automatically search on docker hub to find the right img and pull it

# Stop a conainter
docker stop {container id}

# Start a container (re-use the old)
docker start {container id}

# Port binding (--publish or -p)
docker run -p {HOST_PORT}:{PORT_ON_CONTAINER} {name}:{tag}

# We can give container a name using --name when run it
docker run --name hello-world...
```
