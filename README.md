[Original repo](https://hub.docker.com/r/fnsys/dockhand)  
[Original git-repo](https://github.com/Finsys/dockhand)  

[Custom repo](https://hub.docker.com/r/n00b1k/dockhand-lite)  
Deleted:
- docker-cli
- docker-compose
- docker-cli-buildx
- git

  
### Install
```
docker run -d --name dockhand-lite -p 3000:3000 -v /var/run/docker.sock:/var/run/docker.sock:ro -v /opt/dockhand-lite:/app/data --restart unless-stopped n00b1k/dockhand-lite:1.0.18
```
### Create user
Settings - Authentication - Users - Add user  
Authentication - on  
reload page and login  
Settings - Environments - Add  environment
