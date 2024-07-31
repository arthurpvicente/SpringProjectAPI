# Use uma imagem base do OpenJDK
FROM openjdk:17-jdk-slim

# Adicione um diretório para a aplicação
WORKDIR /app

# Exponha a porta em que a aplicação Spring Boot vai rodar
EXPOSE 8080

# Comando para rodar a aplicação
ENTRYPOINT ["java", "-jar", "app.jar"]
