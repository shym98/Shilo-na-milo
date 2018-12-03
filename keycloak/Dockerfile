FROM jboss/keycloak
WORKDIR /opt/jboss
ADD keycloak /opt/jboss/keycloak
USER root
RUN chmod -R ugo+rwx /opt/jboss/keycloak
EXPOSE 8081
ENTRYPOINT ["./keycloak/bin/standalone.sh", "-b=0.0.0.0"]
