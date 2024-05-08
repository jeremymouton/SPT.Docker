<div align=center style="text-align: center;">
<h1>SPT-Aki - Dockerized</h1>
<h2>Quickly set up your personal Escape from Tarkov server in just 5 minutes..</h2>
<h2>The Linux Container, that builds the server too</h2>
<h4>Why? Because everyone should be able to build, and not rely on unknown builds from unknown sources.</h3>

Platform independent.

This fork simply removes the SIT(stayintarkov) requirements to make a generic SPT-Aki server. Huge thanks to devbence/bullet for the original project.
</div>

---

## Requirements

Install [Docker](https://docs.docker.com/engine/install/).

## Build

The first time you setup the server or update versions, run the `build` command:
```
docker-compose build
```

## Run

To start the container, run:
```
docker-compose up
```

Optionally, start the container in the background with the `-d ` flag:

```
docker-compose up -d
```

## Finish Setup

Go to the `./server` directory, delete `delete_me`, and optionally install additional mods, make config changes, etc.
