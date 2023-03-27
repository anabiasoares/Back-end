Digest: sha256:5cd86fc824e33ac3f9e4c9020c5b328958c6d5e1cb0af5d3154d03ca15fb5ddc
Status: Downloaded newer image for debian:stable-slim
docker.io/library/debian:stable-slim
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ docker container run -it debian:stable-slim
root@2edb16868756:/# cat /etc/*-release
PRETTY_NAME="Debian GNU/Linux 11 (bullseye)"
NAME="Debian GNU/Linux"
VERSION_ID="11"
VERSION="11 (bullseye)"
VERSION_CODENAME=bullseye
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
root@2edb16868756:/# exit
exit
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ docker container ls -a
CONTAINER ID   IMAGE                COMMAND   CREATED              STATUS                      PORTS     NAMES
2edb16868756   debian:stable-slim   "bash"    About a minute ago   Exited (0) 19 seconds ago             epic_stonebraker
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ docker start 2e
2e
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ docker container ls -a
CONTAINER ID   IMAGE                COMMAND   CREATED              STATUS          PORTS     NAMES
2edb16868756   debian:stable-slim   "bash"    About a minute ago   Up 10 seconds             epic_stonebraker
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ docker attach 2e
root@2edb16868756:/# cat /etc/debian_version
11.6
root@2edb16868756:/# exit
exit
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ docker container rm 2e
2e
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ docker container ls -a
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
anabibi@anabibi-HP-14-Notebook-PC:~/TRYBE EXERCISES/Back-end/DOCKER/day one!$ 

