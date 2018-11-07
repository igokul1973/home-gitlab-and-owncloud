FROM node:8.11-jessie

RUN apt update && apt install -y git

# Setup of bash environment
COPY src/bash/.bashrc /root/.bashrc
COPY src/bash/.vimrc /root/.vimrc
COPY src/bash/.vim /root/.vim
COPY src/bash/.inputrc /root/.inputrc

RUN npm i -g npm@latest @angular/cli

ARG app_root

RUN mkdir $app_root

WORKDIR $app_root
