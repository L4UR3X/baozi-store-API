# Baozi Store - API REST
Java 17 · Spring Boot 3 · Spring Data JPA · H2

## Como rodar
    mvn spring-boot:run
API em http://localhost:8080  (console H2: http://localhost:8080/h2-console, JDBC URL `jdbc:h2:file:./data/baozidb`, user `sa`, senha vazia)

## Endpoints
| Entidade | POST | GET (todos) | GET /{id} | DELETE /{id} | PUT /{id} |
|---|---|---|---|---|---|
| Cliente | /clientes | /clientes | /clientes/{id} | /clientes/{id} | /clientes/{id} (opcional) |
| Produto | /produtos | /produtos | /produtos/{id} | /produtos/{id} | /produtos/{id} (opcional) |
| Pedido  | /pedidos  | /pedidos  | /pedidos/{id}  | /pedidos/{id}  | - |
