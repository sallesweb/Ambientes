# Docker
## Instalação
- sudo apt-get update
- sudo apt-get upgrade
- sudo apt install docker.io

## Configuração do serviço Docker
- sudo systemctl start docker
- sudo systemctl enable docker
- sudo systemctl status docker

## Comandos Docker
- docker
- docker -v

## Imagem Docker para teste
- sudo docker run hello-world
- sudo apt install docker-compose
- docker-compose version
- docker container ls
    - sudo groupadd docker
    - sudo gpasswd -a ${USER} docker
    - su - $USER

## Referências
- https://www.youtube.com/watch?v=5ClRVHS0cCg