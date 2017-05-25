FROM docker.elastic.co/logstash/logstash:5.4.0
RUN rm -f /usr/share/logstash/agent/
ADD agent/ /usr/share/logstash/agent/
EXPOSE 9600 5044
CMD ["-f", "/usr/share/logstash/agent/logstash.conf"]
