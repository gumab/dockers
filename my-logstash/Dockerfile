FROM docker.elastic.co/logstash/logstash:6.0.0

COPY logstash.conf /myconfigs/

EXPOSE 5044:5044
EXPOSE 9600:9600
EXPOSE 9900:9900

CMD ["-f", "/myconfigs/logstash.conf"]
