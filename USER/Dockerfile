FROM almalinux:9
#  first we do execute the commands that require root acess, last we use USER before CMD
RUN useradd roboshop
RUN dnf install nginx -y

USER roboshop
CMD ["sleep", "100"]