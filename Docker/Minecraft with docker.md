This is where I store what I've done to make a Minecraft vanilla server
# Pull the image
```shell
docker pull marctv/minecraft-papermc-server:1.21.8-11
```
# Run the image
```shell
docker run -d \
  --name mcserver \
  -it \
  --restart=unless-stopped \
  -e MEMORYSIZE="4G" \
  -p 25565:25565/tcp \
  -p 25565:25565/udp \
  -v /home/hung/minecraft:/data:rw \
  marctv/minecraft-papermc-server:1.21.8-11

```
To know what `-it` is, [[Commands]]