# Minecraft Hunger Games

## Usage
```
docker build -t minecraft .
docker run -it -p 25565:25565 --restart always --name minecraft minecraft
```

Monitor server with
```
docker logs -f minecraft
```
