<h1 align="center">Automobile Service</h1>


## Описание
<p align="left">
Automobile Service - сервис, который управляет информацией об автопарке.
У каждой машины есть уникальный номер, дата сборки и она принадлежит Владельцу.
Владелец машины имеет ФИО, телефон, электронную почту и магины которыми владеет.
Дилер - это организация, у которой есть название, электронная почта, ФИО представителя и она обслуживает несколько пользователей.
Сервис позволяет создавать владельцев машин, машины и дилеров. Назначать и удалять машины владельцам, назначать и удалять владельцев дилерам.
Сервис выводит информацию по каждому дилеру(какие у дилеров обслуживаются владельцы, какие у дилера обслуживаются машины), по каждому владельцу какими машинами он владеет и подробную информацию о каждой машине.

<b>Stack: </b>Java, Spring Boot, Spring MVC, thymeleaf. Для хранения данных используется h2 database.</p>
## Инструкция по запуску
### Последовательность:
1. Сделать git clone проекта
2. Из корневой папки проекта запустить команду:```mvn spring-boot:run``` 
3. После того как сервис запустится, он будет доступен на 8090 порту.
4. Ready

Сервис доступен по ссылке:
#### http://localhost:8090/autoservice/

