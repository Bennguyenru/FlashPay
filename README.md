# FlashPay Application
This is a collaborative project named as Payment Wallet Application(FlashPay) which is our Backend project build by a team of 4 in just 5 days.
By using this application one can send and receive money, pay different bills, view transaction details, add balance to wallet etc.. 

## Entity Relationship Diagram 
 
<img src="https://user-images.githubusercontent.com/101569228/200902071-d6ad123d-55ce-4dee-b7bd-6d5c3a06ee0b.jpeg" alt="" width="860" height="820">

## Services Offered 

- User Login and Signup.
- Add money from bank account to wallet.
- Transfer money from wallet to wallet.
- Deposit Money from wallet to Bank Account.
- User can pay different different bills.
- User can get all transaction history, bill payments.

## Backend Work

- Built authentication while login and logout using key.
- Stored data on MySQL.
- Input Validation.
- Implement Login and logout Functionality with CurrentSeesionUser table.

## Technology Used

- Java
- Spring
- Spring Boot
- Spring data JPA
- Hibernate
- MySQL

## Installation & Run

- Before running the API server, you should update the database config inside the application.properties file.
- Update the port number, username and password as per your local database config.

```
server.port=8038

#db specific properties
spring.datasource.url=jdbc:mysql://localhost:3306/flashpaydb
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=root

#ORM s/w specific properties
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

spring.mvc.pathmatch.matching-strategy = ANT_PATH_MATCHER

```

## API Root Endpoint

https://localhost:8038/

 ## Team Members

### [Akshay Boraste](https://github.com/akbora1994)
### [Sushank Mandal](https://github.com/sushank678)
### [Subhajit](https://github.com/subhajit51193)
### [Deepak Sharma](https://github.com/Deepaksharma-39)
