FROM redhat/ubi9
RUN dnf install -y nginx
EXPOSE 80
ENV MONGO_URL=mongo-dev.happielearning.com \
    CATALOGUE_URL=catalogue-dev.happielearning.com
CMD ["nginx", "-g", "daemon off;"]