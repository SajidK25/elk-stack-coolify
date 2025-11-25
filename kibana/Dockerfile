FROM docker.elastic.co/kibana/kibana:9.2.1

USER root
COPY kibana.yml /usr/share/kibana/config/kibana.yml
RUN chown kibana:kibana /usr/share/kibana/config/kibana.yml
USER kibana