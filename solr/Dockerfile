FROM solr
WORKDIR /opt/solr/server/solr/
ADD services /opt/solr/server/solr/services
ADD postgresql-42.2.5.jar /opt/solr/contrib/dataimporthandler/lib
USER root
RUN chown -R solr /opt/solr/server/solr
USER solr
