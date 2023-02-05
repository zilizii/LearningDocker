# LearningDocker
Build up basic Docker knowledge - Mosquitto, Nodered,...

## Project Scope:
to have a running base for my Home Automation system, the choosen components:
 - raspberry 3 with Raspbian OS
 - Docker installed : https://pimylifeup.com/raspberry-pi-docker/
 - docker-compose installed : sudo apt install docker-compose
 - install Portainer
   - sudo docker pull portainer/portainer-ce:latest
   - sudo docker run -d -p 9000:9000 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest
 
 - Nodered and MQTT Broker : Mosquitto will used
   - mkdir Docker
   - cd Docker/
   - docker-compose -f docker-compose.yaml up -d
 
