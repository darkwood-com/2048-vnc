# 2048-vnc

A docker version of 2048 on VNC (600x800)

Based on [gabrielecirulli/2048](https://github.com/gabrielecirulli/2048)

# Usage

    docker run -d --name 2048 -p 5901:5901 -it -e USER=firefox matyo91/2048-vnc

then connect vnc://eval $(docker-machine ip 2048):5901 with password azertyui
