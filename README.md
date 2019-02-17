# Minecraft Server

Minecraft PC server & Minecraft PE server, build with docker.

# Deploy

## Clone this project

`git clone https://github.com/DevinDon/minecraft.git`

## Start docker

`docker-compose up --build`

*If you want to run in background, add -d parameter, like this:*

`docker-compose up -d --build`

# Minecraft PC(Java)

version: 1.13.2

port: 25565 / TCP

# Minecraft PE(Bedrock)

version: 1.9.15

port: 19132 / UDP
