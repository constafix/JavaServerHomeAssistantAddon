FROM eclipse-temurin:17-jdk-alpine

WORKDIR /app

# Копируем JAR и скрипт запуска
COPY original-java-hass-addon-1.0.0.jar app.jar
COPY run.sh /run.sh

RUN chmod +x /run.sh

CMD ["/run.sh"]