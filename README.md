# jenkins-demo

## Build jenkins + blueocean image
```bash
docker build -t myjenkins-blueocean:2.387.3-1 .
```

## Start container jenkins + blueocean
```bash
chmod +x start-jenkins-blueocean.sh
./start-jenkins-blueocean.sh
```

## Get admin password to login to jenkins ui
```bash
chmod +x get-admin-password.sh
./get-admin-password.sh
```

## 

References:
- Jenkins install with Docker: https://www.jenkins.io/doc/book/installing/docker/ 