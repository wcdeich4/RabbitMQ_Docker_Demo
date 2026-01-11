RabbitMQ Docker setup
======================================================================================================= 
sudo dnf config-manager addrepo --from-repofile https://download.docker.com/linux/fedora/docker-ce.repo
sudo dnf install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
sudo systemctl enable --now docker
sudo docker pull rabbitmq:management-alpine
sudo docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4-management


sources
-------------------------------------------------------- 
https://docs.docker.com/engine/install/fedora/
https://www.rabbitmq.com/tutorials/tutorial-one-dotnet
https://www.rabbitmq.com/docs/download
https://hub.docker.com/_/rabbitmq/