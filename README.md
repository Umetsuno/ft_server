# ft_serveur

## CHEAT SHEET

### http://127.0.0.1
### http://127.0.0.1/phpMyAdmin/
### http://127.0.0.1/wordpress/

**FROM** *defines the source img*

**RUN** *executes commands inside the docker*

**ADD** *adds files inside the docker*

**WORKDIR** *defines your workspace*

**EXPOSE** *enter the port number on which the SSH server is listening*

**VOLUME** *defines the usable sound output*

**CMD** *defines the default command when your docker is running*

## EXAMPLES

- **docker run**
- **docker run -p 80:80 nginx** : *-p is the suitable option to choose your port(s)*
- **docker stop** : *returned_docker_ID if it was created with --detach*
- **docker rm** : *returned_docker_run_ID*
- **docker ps** : *active dockers display*
- **docker images -a** : *displays absolutly every ISO image*
- **docker system prune** : *clean everything*

- *docker build -t <chosen name> .*
- *docker run -p 80:80 -p 443:443 -it <chosen name> bash*
- *service nginx start*
