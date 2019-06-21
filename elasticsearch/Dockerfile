ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch-oss:${ELK_VERSION}

ARG ELK_VERSION

# 停用词: https://www.ranks.nl/stopwords
RUN elasticsearch-plugin install -b https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${ELK_VERSION}/elasticsearch-analysis-ik-${ELK_VERSION}.zip
