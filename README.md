# dckr (just a bunch of docker shortcuts)

## Usage

```
Usage: dckr.sh <subcommand> [options]

Subcommands:
    ip    CONTAINER   Get a container's ip
    links CONTAINER   Get a container's links
    env   CONTAINER   Get a container's environment variables
    cmd   CONTAINER   Get a container's command
    volf  CONTAINER   Get a container's volumes_from
    vols  CONTAINER   Get a container's volumes

DANGERZONE (don't mess with this shit... seriously):
    clean    Remove ALL exited containers and remove unused images
    kill     Stop ALL running containers and remove them
    nuke     Stop ALL running containers, remove them and delete ALL images
    reset    alias for 'nuke'
```

## Installation