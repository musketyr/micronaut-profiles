FROM openjdk:8u171-alpine3.7
RUN apk --no-cache add curl
COPY target/@app.name@*.jar @app.name@.jar
CMD java ${JAVA_OPTS} -jar @app.name@.jar