FROM debian
ENV USER "dockerapp"
RUN adduser $USER
RUN apt update && apt install -y openjdk-11-jre curl nmap
USER $USER
RUN cd&&  curl https://pub.tutosfaciles48.fr/mirrors/apache/kafka/2.6.0/kafka_2.13-2.6.0.tgz --output kafka.tgz  && tar -xzf kafka.tgz
RUN cd&& mv kafka_2.13-2.6.0 kafka && rm kafka.tgz

