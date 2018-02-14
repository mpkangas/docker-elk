FROM docker.elastic.co/logstash/logstash:6.2.0

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-filter-ruby
RUN logstash-plugin install logstash-input-redis
RUN logstash-plugin install logstash-input-beats
RUN logstash-plugin install logstash-output-hipchat
