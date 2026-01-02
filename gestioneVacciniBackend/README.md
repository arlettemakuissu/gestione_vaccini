\# Gestione Vaccini



Applicazione full-stack per la gestione dei vaccini.



Il progetto è composto da:

\- una \*\*parte frontend\*\* sviluppata in React JS

\- una \*\*parte backend\*\* sviluppata in Spring Boot



---



\## Tecnologie utilizzate



\### Frontend

\- React JS

\- JavaScript

\- HTML5

\- Bootstrap

\- CSS



\### Backend

\- Java 17

\- Spring Boot (stessa versione del progetto Tour)

\- Maven

\- Tomcat

\- Spring Data JPA

\- MySQL



---



\## Struttura del progetto



\- `gestioneVaccini/` → Backend Spring Boot

\- `gestionevaccinifontend/` → Frontend React

\- `.gitignore` → file ignorati da Git

\- `pom.xml` → dipendenze Maven

\- `package.json` → dipendenze frontend



---



\## Installazione e avvio



\###  Clonare il repository



```bash

git clone https://github.com/arlettemakuissu/gestioneVaccini.git

cd gestioneVaccini

 Avvio Backend

cd gestioneVaccini

mvn clean install

mvn spring-boot:run

Il backend sarà disponibile su:







http://localhost:8080

 Avvio Frontend

bash



cd gestionevaccinifontend

npm install

npm start

Il frontend sarà disponibile su:







http://localhost:3000

Database

Il progetto utilizza MySQL.



Configurazione nel file application.properties:



properties



spring.datasource.url=jdbc:mysql://localhost:3306/gestione\_vaccini

spring.datasource.username=root

spring.datasource.password=\*\*\*\*


