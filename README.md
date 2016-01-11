![beevelop/dckr](/logo.png?raw=true)

# dckr (just a bunch of docker shortcuts)

## Usage

```
Usage: dckr <subcommand> [options]

Subcommands:
    ip    CONTAINER   Get a container's ip
    links CONTAINER   Get a container's links
    env   CONTAINER   Get a container's environment variables
    cmd   CONTAINER   Get a container's command
    volf  CONTAINER   Get a container's volumes_from
    vols  CONTAINER   Get a container's volumes

    images   List images with their size (requires 'sh' and 'du' command)

DANGERZONE (don't mess with this shit... seriously):
    clean    Remove ALL exited containers and remove unused images
    kill     Stop ALL running containers and remove them
    nuke     Stop ALL running containers, remove them and delete ALL images
    reset    alias for 'nuke'
```

## Installation

### [Basher](https://github.com/basherpm/basher) (recommended)
```
basher install beevelop/dckr
```

### Manually (definitely not recommended)
> Basher hugely simplifies the hassle to update **dckr** and stay up-to-date with the latest development. Therefore installing manually is **not recommended**. 

```
git clone https://github.com/beevelop/dckr ~/.dckr

# Add ~/.dckr to your PATH env by running one of the following commands
echo 'export PATH="$HOME/.dckr:$PATH"' >> ~/.bash_profile
# Or on Ubuntu Desktop
echo 'export PATH="$HOME/.dckr:$PATH"' >> ~/.bashrc
# Or for zsh <3
echo 'export PATH="$HOME/.dckr:$PATH"' >> ~/.zshrc
```
