# Discord-Bot-Maker-Host

## Perpuse

A simple Docker image able to run the Discord bot which base on node.js or made by  [Discord Bot Maker (DBM)](https://store.steampowered.com/app/682130/Discord_Bot_Maker/ "Discord Bot Maker")

## Delploy on Docker
```
docker run -d \
  --name discord-bot \
  -v path_to_your_bot_folder:/app \
  1030283726/discord-bot-maker-host
```
## Dockerfile
```
FROM node:latest

WORKDIR /app

CMD ["node", "bot.js"]
```

