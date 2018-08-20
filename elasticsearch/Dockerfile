FROM docker.elastic.co/elasticsearch/elasticsearch:6.2.0

RUN elasticsearch-plugin remove x-pack

RUN elasticsearch-plugin install --batch x-pack
