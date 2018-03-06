FROM docker.elastic.co/elasticsearch/elasticsearch:6.2.0

ENV ES_JAVA_OPTS="-Des.path.conf=/etc/elasticsearch"

RUN elasticsearch-plugin remove x-pack

RUN elasticsearch-plugin install --batch x-pack
