When running a service via [[Containers]], we'll want to access it via `localhost` or something like that. But the service is running on it own *kind of virtual* environment, so we need to have a *bridge* to access it called **port binding**
how to do port binding? [[Commands]]
`docker run -p {HOST_PORT}:{PORT_ON_CONTAINER} {name}:{tag}`
Now we can access the service via
``` txt
localhost:{HOST_PORT}
or
# if we want to access service from another device (in the same network)
{Private IP of host}:{HOST_PORT}
```
