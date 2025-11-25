FROM docker.elastic.co/logstash/logstash:9.2.1

USER root
COPY logstash.yml /usr/share/logstash/config/logstash.yml
COPY logstash.conf /usr/share/logstash/pipeline/logstash.conf
RUN chown logstash:logstash /usr/share/logstash/config/logstash.yml \
    /usr/share/logstash/pipeline/logstash.conf
USER logstash
