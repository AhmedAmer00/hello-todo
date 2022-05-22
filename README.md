# Description:
- This project create an API for Todo Application using:
- Java Core, Java EE
- IDE: -
      - Netbeans 
      - insomia 
it's an simple project for start to understand the concept of Java EE

# Build
mvn clean package && docker build -t academy.learnprogramming/hello-todo .

# RUN

docker rm -f hello-todo || true && docker run -d -p 8080:8080 -p 4848:4848 --name hello-todo academy.learnprogramming/hello-todo 
