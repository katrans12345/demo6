FROM masstroy/alpine-docker-java-maven
RUN apk update
RUN apk add git
RUN mkdir /home/Project
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git /home/Project
ADD mvnbuild.sh /home/Project/mvnbuild.sh
ENTRYPOINT ["/home/Project/mvnbuild.sh"]