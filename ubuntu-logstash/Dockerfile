FROM ubuntu-java:latest
RUN adduser --quiet --disabled-password --gecos "" muser
RUN apt-get install -y vim
RUN wget -P /home/muser/ https://artifacts.elastic.co/downloads/logstash/logstash-6.0.0.tar.gz
RUN wget -P /home/muser/ https://artifacts.elastic.co/downloads/kibana/kibana-6.0.0-linux-x86_64.tar.gz
RUN wget -P /home/muser/ https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-6.0.0.tar.gz
RUN chown muser:muser /home/muser/*.tar.gz