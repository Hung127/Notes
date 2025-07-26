# Duck dns
This is my token for [[Minecraft with docker]]
> [!question]- This is my duck dns token
>`906b6aaf-6344-4499-b92a-7a004db6a163`
> cuanam.duckdns.org

this is a container that update my ip to duck dns
``` shell
docker run -d \
  --name=duckdns \
  --net=host `#optional` \
  -e PUID=1000 `#optional` \
  -e PGID=1000 `#optional` \
  -e TZ=Asia_Ho_Chi_Minh `#optional` \
  -e SUBDOMAINS=cuanam \
  -e TOKEN=906b6aaf-6344-4499-b92a-7a004db6a163 \
  -e UPDATE_IP=ipv4 `#optional` \
  -e LOG_FILE=false `#optional` \
  -v /home/hung/duckdns-docker:/config `#optional` \
  --restart unless-stopped \
  lscr.io/linuxserver/duckdns:latest
```
