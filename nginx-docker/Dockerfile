




FROM ubuntu
RUN apt update
RUN apt install -y nginx
RUN apt install -y vim
COPY apt_script.sh /bin/
RUN chmod +x /bin/apt_script.sh
RUN chmod +rwx -R /bin
RUN /bin/apt_script.sh
