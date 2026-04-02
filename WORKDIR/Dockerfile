FROM almalinux:9
RUN mkdir /tmp/workdir-demo
# RUN cd /tmp/workdir-demo
# WORKDIR is used to set the working directory for any RUN, CMD, ENTRYPOINT, COPY and ADD instructions that follow it in the Dockerfile. If the directory does not exist, it will be created.
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo "Hello I am in work dir" > hello.txt
CMD ["sleep","1000"]