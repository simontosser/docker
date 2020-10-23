FROM kafka-base
ENV USER "dockerapp"
USER $USER
EXPOSE 2181
CMD cd && cd kafka && bin/zookeeper-server-start.sh config/zookeeper.properties 
