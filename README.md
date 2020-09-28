# Ubuntu 20.04 Python 3.8
# HTTPAceProxy® https://github.com/pepsik-kiev/HTTPAceProxy
# Acestream 3.1.49

# Slightly modified version to include ffmpeg for easy replication of streams

`docker run -d --net host -e PGID=0 -e PUID=0 --restart always --privileged --name proxy2 -e TZ=Europe/Moscow tarmets/httpaceproxy2`

`docker exec -it proxy2 /bin/bash`

`http://your_server_ip:6878/webui/app/password/server?#proxy-server-playlist`


`http://your_server_ip:8585/torrenttv/playlist.m3u`


`http://your_server_ip:8585/stat`

