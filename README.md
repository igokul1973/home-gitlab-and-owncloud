# home-gitlab-and-owncloud

## Description
The project deploys dockerized Nginx proxy that caters to Owncloud and GitLab services. All the services are created using images from Docker Hub.

## Requirements
1. This project uses .env file in its root. Please provide the following in the file:
```
GITLAB_DOMAIN=xxx.com 						# provide domain name for the GitLab service
OWNCLOUD_VERSION=10.0.2 					# please choose the right version
OWNCLOUD_DOMAIN=xxx.com						# provide domain name for the GitLab service
OWNCLOUD_ADMIN_USERNAME=username			# provide the administrator username that will be used upon the first login
OWNCLOUD_ADMIN_PASSWORD=password			# provide the administrator password that will be used upon the first login
```

