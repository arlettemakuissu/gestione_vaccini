#  Gestione Vaccini

Applicazione web per la gestione dei vaccini.



##  Tecnologie utilizzate

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

### Frontend
- React
- JavaScript
- HTML5
- CSS3
- Bootstrap


###  Database

Il progetto utilizza MySQL come database relazionale.

La gestione delle tabelle è affidata a Spring Data JPA e Hibernate.
Le tabelle vengono create automaticamente all’avvio dell’applicazione
in base alle entità definite nel backend.

Ogni sviluppatore deve configurare localmente le credenziali del database
nel file `application.properties`.

## Struttura del progetto

gestioneVaccini/
├── gestioneVacciniBackend/
│   ├── src/
│   └── pom.xml
│
├── gestioneVacciniFrontend/
│   ├── src/
│   └── package.json
│
└── README.md

---

##  Avvio Backend (Spring Boot)

cd gestioneVacciniBackend  
./mvnw spring-boot:run

Backend disponibile su:  
http://localhost:8081

---

##  Avvio Frontend (React)

cd gestioneVacciniFrontend  
npm install  
npm start

Frontend disponibile su:  
http://localhost:3000



## Comunicazione

Il frontend comunica con il backend tramite API REST (JSON).



## 👤 Autore
Arlette Makuissu.



## Licenza
Progetto a scopo didattico, realizzato per apprendere e mettere in pratica lo sviluppo di applicazioni full-stack con Spring Boot e React.