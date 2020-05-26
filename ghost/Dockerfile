FROM ghost:3.16.1
RUN apt-get update -y && \
    apt-get install -y mariadb-client-10.3
COPY ./wait-for-it.sh /usr/local/bin/wait-for-it.sh
