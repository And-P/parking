<div align="center">

  <img src="assets/parking.png" alt="Logo" height="200">
  <h2 align="center"><strong>Parking</strong></h1>
  <p align="center">
      This project simulates a Parking API. Demontrate some Rest-API concepts. Calculate the bill using an entry-date-time and exit-date-time information. It is a practical experience in order to show knowledge about the architecture and technologies applied during its development.  
  </p>

</div>

<br />

#### Technologies

This code source was developed with the following items:

- [Java][SDK 17] 
- [SpringBoot][2.7.5] 
- [Spring Security][Basic Auth - WebSecurityConfigurerAdapter] 
- [Swagger][2.9.2]
- [Model Mapper][2.3.5]
- [PostgresSQL][Database]
- [Rest-Assured][test]
- [Maven][3.8]
- [InteliJ Community Edition][2021.3]


#### How To Use

```bash
# Run database <????> => configure yourself
$ docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=<????> -e POSTGRES_PASSWORD=<????> -d postgres:10-alpine

# Stop database
$ docker stop parking-db

# Start database
$ docker start parking-db
```

#### Author: Me [LinkedIn](https://www.linkedin.com/in/andrp) 

