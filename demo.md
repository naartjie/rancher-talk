## Install Rancher Server
We create a DigitalOcean Docker Droplet, and docker run rancher/server.
```
docker run -d --restart=always -p 80:8080 rancher/server
```
Caveat: differences in production:
 - SSL termination
 - GitHub Authentication
 - Point to something like AWS RDS for your DB


### Log in, and lock down

### Spin up 4 DO hosts

### Let that simmer for a while... (back to talk)

## Create Stacks

### Services stack with service-1 and service-2
Mention that we're not exposing the ports directly

### Add LB
This talks internal networking to the service containers

### Go to browser and show it's working

### Optional: SSL + domain name

## Modify service-1

### Make tweaks

### Docker build

### Docker push

### Run ab

### Redeploy service-1

### Optional: JBoss -> JBaaS
