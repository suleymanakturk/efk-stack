FROM fluentd:v1.17-debian-1
USER root
RUN gem install elasticsearch -v 7.17.0
RUN gem install fluent-plugin-elasticsearch -v 5.0.3
USER fluent
