# ft_serveur

### http://127.0.0.1
### http://127.0.0.1/phpMyAdmin/
### http://127.0.0.1/wordpress/

## CHEAT SHEET

**FROM** *defines the source img*

**RUN** *executes commands inside the docker*

**ADD** *adds files inside the docker*

**WORKDIR** *defines your workspace*

**EXPOSE** *enter the port number on which the SSH server is listening*

**VOLUME** *defines the usable sound output*

**CMD** *defines the default command when your docker is running*

## EXAMPLES

- *docker run*
- *docker run -p 80:80 nginx* : **-p** is the suitable option to choose your port(s)
- *docker stop* ID_RETOURNÉ_LORS_DU_DOCKER_RUN si cree avec --detach
- docker rm ID_RETOURNÉ_LORS_DU_DOCKER_RUN
- docker ps
- docker images -a : la commande pour faire le ménage : docker system prune

- docker build -t <NOM que je veux> .
- docker run -p 80:80 -p 443:443 -it <NOM que je veux> bash
- service nginx start

