# csgo
CSGO Docker-Compose

```
!! 
Project base is the awesome work of
https://github.com/Gonzih/docker-csgo-server
Thanks! :-)
```

## Step 1

Build local csgo Image with latest Updates. Why? You only have to update one image for all servers.

```
cd docker
docker build -t csgo:latest .
```

## Step 2

Start a local deathmatch server

```
docker-compose -f deathmatch.yml up
```


#### Links
http://csgodev.com/csgo-server-command-line-options/
https://pkrhosting.co.uk/knowledgebase/8/How-to-change-the-gamemode-of-the-csgo-server.html
