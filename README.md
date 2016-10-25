![logo](https://hsto.org/files/064/f34/34b/064f3434bba04ad3bb7fbcd091ad810c.png)

# What is NetInstaller?

Custom docker containers with pxe install populates distribution Linux

# NetInstaller images

NetInstaller are based on latest Alpine, jessie Debian and trusty Ubuntu images. The available versions of NetInstaller are:

    NetInstaller Alpine 3.2 (tags: alpine-3.4, alpine-lates, latest)
    NetInstaller Denian Jessie (tags: debian-jessie, debian-latest)  
    NetInstaller Ubuntu Trusty (tags: ubuntu-trusty, ubuntu-latest)

Images are updated when new releases are published. The image with ``latest`` tag is based on Alpine Linux.

# How to use this image

Start a localdef container as follows:

    docker run --name some-name-proyect -e TZ="Europe/Madrid" -e IDIOM="es_ES" --rm -ti westerus/netinstaller:tag
