
This project is to provide a sample that recreates the issue https://github.com/spring-cloud/spring-cloud-config/issues/707.


1. Clone this repo 


2. Build all applications included in this project

```
mvn clean install
```

3. Start rabbit-mq using docker-compose.yml

```
docker-compose up -d 
```

4. Start config-server

```
mvn spring-boot:run
```

5. Start ui
```
mvn spring-boot:run
```

6. Place ui.yml file under /var/shared and make change 


7. See log for ui application

