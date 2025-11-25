FROM docker.elastic.co/beats/filebeat:9.2.1
USER root
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
RUN chmod 600 /usr/share/filebeat/filebeat.yml && \
    chown root:root /usr/share/filebeat/filebeat.yml