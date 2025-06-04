ARG BASE_IMAGE
FROM ${BASE_IMAGE}
COPY CompositeApps/*.car ${WSO2_SERVER_HOME}/repository/deployment/server/carbonapps/
COPY resources/wso2carbon.jks ${WSO2_SERVER_HOME}/repository/resources/security/wso2carbon.jks
COPY resources/client-truststore.jks ${WSO2_SERVER_HOME}/repository/resources/security/client-truststore.jks
# COPY libs/*.jar ${WSO2_SERVER_HOME}/lib/

# Copia el driver PostgreSQL al directorio lib
#COPY libs/postgresql-42.7.5.jar ${WSO2_SERVER_HOME}/lib/