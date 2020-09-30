FROM masstroy/alpine-docker-java-maven
RUN apk update
RUN apk add git
RUN mkdir /home/Project
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git /home/Project
RUN mvn package -f /home/Project/pom.xml