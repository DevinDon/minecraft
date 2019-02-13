FROM ubuntu:bionic
WORKDIR /app
RUN apt update && apt-get install openssl libcurl4-openssl-dev -y
CMD chmod +x bedrock_server && LD_LIBRARY_PATH=. ./bedrock_server
