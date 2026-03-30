FROM almalinux:9
RUN dnf install -y nginx
RUN useradd roboshop

# Use root user for package management or installation
USER roboshop
CMD ["sleep","120"]