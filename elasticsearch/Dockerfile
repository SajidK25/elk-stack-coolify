FROM docker.elastic.co/elasticsearch/elasticsearch:9.2.1

USER root
COPY elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml
RUN chown elasticsearch:root /usr/share/elasticsearch/config/elasticsearch.yml
USER elasticsearch
