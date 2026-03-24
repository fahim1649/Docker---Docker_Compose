# Docker And Docker-Compose Installation_Specific_Version_1.29.2

```javascript
# Install Docker
sudo apt-get update
sudo apt install docker.io -y

# To install specific version of Docker-Compose
cd /home/ubuntu/
wget https://github.com/docker/compose/releases/download/1.29.2/docker-compose-Linux-x86_64
mv docker-compose-Linux-x86_64 docker-compose
sudo mv docker-compose /usr/bin/
sudo chmod +x /usr/bin/docker-compose
docker --version
docker-compose version
```
