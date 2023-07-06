FROM openjdk:alpine
RUN  yum update -y && yum install mysql -y
COPY . /projJenkins
EXPOSE 8080
CMD [ "java", "-jar", "app.jar"]
