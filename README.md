# <img width="40" height="40" src="https://img.icons8.com/?size=100&id=55497&format=png&color=000000" alt="api"/> Тестирование REST и SOAP API с помощью Postman
## Тестирование REST API
Я протестировала все методы, предусмотренные для [demoshopping.ru](https://qa.demoshopping.ru/) и описанные в [документации](https://qa.demoshopping.ru/api-docs/) в Swagger, и создала следующие сущности для тестирования REST API:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/?size=100&id=DZqTzsR-uixC&format=png&color=000000" alt="rest api"/> [Коллекция в Postman](https://www.postman.com/avionics-pilot-14449528/workspace/testing-workspace/collection/40954683-13f80804-00b8-4289-b5a1-516f6fdb4126?action=share&creator=40954683&active-environment=40954683-6fd751e1-b987-46b2-b621-618fe18b3d54) для тестирования модулей Products, Users, Cart, Orders, Payment

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/?size=100&id=DZqTzsR-uixC&format=png&color=000000" alt="rest api"/> [Тест-кейсы](https://github.com/NikolaevaAR/api/blob/main/%D0%A2%D0%B5%D1%81%D1%82%D1%8B-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B%20%D0%B4%D0%BB%D1%8F%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20REST%20API%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%20demoshopping.ru.pdf) для тестирования методов GET, POST, PUT, PATCH, DELETE

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/?size=100&id=DZqTzsR-uixC&format=png&color=000000" alt="rest api"/> [Автотесты в Postman](https://www.postman.com/avionics-pilot-14449528/testing-workspace/request/rmtmmoa/200), проверяющие статус-код, тело ответа, создание сущностей (для метода POST) и тд. Вы также можете ознакомиться с результатами [тестового прогона](https://github.com/NikolaevaAR/api/blob/main/%D0%A0%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B%20%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BE%D0%BD%D0%B0%20%D0%B4%D0%BB%D1%8F%20demoshopping.ru%20%D0%B2%20Postman.json) в Postman.


## Тестирование SOAP API
Также я протестировала SOAP-сервис, используя следующий [WSDL](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL), где описаны методы, позволяющие получить различную информацию о целевой стране, и создала коллекцию в Postman для тестирования данного SOAP-сервиса:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img width="25" height="25" src="https://img.icons8.com/?size=100&id=DZqTzsR-uixC&format=png&color=000000" alt="soap api"/> [Коллекция в Postman](https://www.postman.com/avionics-pilot-14449528/workspace/testing-workspace/collection/40954683-1d64366e-78ef-420b-96f4-5b51f79b153b?action=share&creator=40954683&active-environment=40954683-6fd751e1-b987-46b2-b621-618fe18b3d54) для тестирования SOAP-сервиса
