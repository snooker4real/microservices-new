# microservices-new

**Stack** : Java 17, Maven, Spring Boot 3.0.5, Testcontainers

## Démarrage

```bash
mvn clean install   # construire et tester
mvn spring-boot:run   # démarrer l'application
mvn test   # lancer les tests
```

## Docker

```bash
docker compose -f docker-compose.yml up --build
```

## Structure

```
discovery-server/
inventory-service/
order-service/
product-service/
Jenkinsfile
docker-compose.yml
pom.xml
```
