FROM ubuntu:22.04

RUN apt-get update \
&& apt-get install -y wget python3 python3-pillow python3-dev python3-numpy

RUN wget -O /tmp/overviewer.deb https://github.com/GregoryAM-SP/The-Minecraft-Overviewer/releases/download/1.21.0/overviewer-v1.21.0-x86_64-ubuntu-22.04.deb \
&& dpkg -i /tmp/overviewer.deb \
&& rm /tmp/overviewer.deb

CMD ["/bin/bash"]