Commands:
```
docker run -d --restart=always -p 80:8080 rancher/server:stable

for i in {1..5000}; do curl http://45.55.142.34/; echo; done;

ab -lr -c 500 -n 1000 http://45.55.142.34/
```

## Install Rancher Server
We create a DigitalOcean Droplet with Docker, and docker run rancher/server.
```
docker run -d --restart=always -p 80:8080 rancher/server:stable
```
Caveat: differences in production:
- Domain name
- SSL termination
- GitHub Authentication
- Point to something like AWS RDS for your DB

### Log in, and lock down

### Spin up 4 DO hosts

### Let that simmer for a while... (back to talk)

.... UI + CLI + API

## Create Stack

### Services stack with service-1 and service-2
Mention that we're not exposing the ports directly

### Add LB
This talks internal networking to the service containers

### Go to browser and show it's working


## Modify service-1

### Make tweaks

### Docker build

### Docker push

### Run ab

### Redeploy service-1

TODO: say UI + CLI + API
Optional: SSL + domain name
