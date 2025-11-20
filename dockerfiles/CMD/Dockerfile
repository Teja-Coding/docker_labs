FROM almalinux:9
RUN dnf install nginx -y
# CMD [ "systemctl","start","nginx" ]  ---> this will not work in inside container
CMD ["nginx","-g","daemon off;"]