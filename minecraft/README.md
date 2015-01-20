## Usage
```
docker run --rm -p 25565:25565 -p 25575:25575 hisetu/minecraft
```

### Server configuration

```
docker run --rm -p 25565:25565 -p 25575:25575 -e EULA=TRUE -e NOAUTH=TRUE -e NOPVP=TRUE -e RCONPASSWD=password -e MOTD=message hisetu/minecraft
```