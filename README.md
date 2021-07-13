# wordpress-docker-xdebug 
setup wordpress local dev env 

#Windows
1. install git and git bash 
2. install wsl2 https://docs.microsoft.com/en-us/windows/wsl/install-win10
3. install docker desktop https://docs.docker.com/docker-for-windows/wsl/

## docker
- login to container `docker exec -it <container_id> bash`
- build image `docker-compose build`

## source mapping (phpstorm)
1. <root path>/wordpress -> /var/www/html
2. <root path>/plugins -> /var/www/html/wp-content/plugins

# wordpress-docker-xdebug-wsl2
