FROM nginx:1.15

# Setup of bash environment
COPY src/bash/.bashrc /root/.bashrc
COPY src/bash/.vimrc /root/.vimrc
COPY src/bash/.vim /root/.vim
COPY src/bash/.inputrc /root/.inputrc

COPY src/nginx/angular.mironov/nginx.conf /etc/nginx/conf.d/
COPY kupishuzi.ru/dist /usr/src/app
