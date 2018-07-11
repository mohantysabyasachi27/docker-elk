# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:6.3.0

# Add your logstash plugins setup here
RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-elapsed
RUN logstash-plugin install logstash-filter-date
RUN logstash-plugin install logstash-output-elasticsearch
