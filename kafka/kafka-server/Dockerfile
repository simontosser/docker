FROM kafka-base
ENV USER "dockerapp"
USER $USER
COPY server.properties /home/dockerapp/kafka/config/server.properties
EXPOSE 9092 9093
CMD cd && cd kafka && bin/kafka-server-start.sh config/server.properties
