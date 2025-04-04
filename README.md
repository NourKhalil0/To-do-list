# ToDo List , Spring Boot Backend

Heiheiheihei!! 

Dette er min aller første prosjekt uten noe hjelp av Google eller KI (:

En enkel backend applikasjon for en ToDo-liste bygget med Spring Boot og PostgreSQL . Applikasjonen lar deg opprette, hente, oppdatere og slette oppgaver (tasks).




# Teknologier brukt

- Java 17+
- Spring Boot
- Spring Data JPA
- PostgreSQL
- REST API
- Maven

#Endepunkter

| Metode | Endpoint       | Beskrivelse                 |
|--------|----------------|-----------------------------|
| GET    | /tasks         | Henter alle oppgaver        |
| GET    | /tasks/{id}    | Henter en oppgave med id    |
| POST   | /tasks         | Oppretter en ny oppgave     |
| PUT    | /tasks/{id}    | Oppdaterer en oppgave       |
| DELETE | /tasks/{id}    | Sletter en oppgave          |

#  Oppsett lokalt

1. Klon repoet:
   ```bash
   git clone https://github.com/brukernavn/todo-backend.git

2. Gå inn i prosjektmappen:
"cd todo-backend"

3. Konfigurer application.properties med din PostgreSQL database.

4. Kjøøørrrrr: ./mvnw spring-boot:run


PS: Bruk PostgreSQL og sørg for at du har en database kalt f.eks. todo_db. Tabeller genereres automatisk takket være JPA 

