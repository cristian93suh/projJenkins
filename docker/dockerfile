FROM openjdk:alpine
run  yum update -y && yum install mysql -y
COPY . .
EXPOSE 8080
CMD [ "java", "-jar", "app.jar"]
