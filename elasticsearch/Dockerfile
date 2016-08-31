FROM elasticsearch:2.3
MAINTAINER Junichiro Kashiwa <cushy79@gmail.com>
WORKDIR /usr/share/elasticsearch
RUN bin/plugin install cloud-aws 
COPY docker-entrypoint.sh /docker-entrypoint.sh
