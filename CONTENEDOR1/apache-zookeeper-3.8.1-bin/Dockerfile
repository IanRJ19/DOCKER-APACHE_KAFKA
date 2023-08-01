FROM eclipse-temurin:11-jre

ARG ZOO_USER_HOME=/usr/local/zookeeper
ENV ZOO_HOME=${ZOO_USER_HOME}

WORKDIR ${ZOO_HOME}

COPY . .

EXPOSE 2181 2888 3888

CMD ["bin/zkServer.sh", "start-foreground"]

