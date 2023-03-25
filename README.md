# HTTP, Client server architecture, OSI-model

#### HTTP:

| Термин | Описание |
| :----------------- | :------------------ |
| HTTP | Протокол передачи гипертекста, протокол прикладного уровня для обмена данными между двумя звеньями в сети |
| Протокол |	Набор правил и договорённостей для обмена данными между двумя или более устройствами в сети |
| HTTP methods | Методы, которые определяют тип запроса, используемый для обмена данными между двумя звеньями в системе: GET, POST, PUT, PATCH, DELETE, OPTIONS |
| OPTIONS	| Метод, который используется для запроса информации о доступных методах HTTP на сервере |
| HTTP body	| Данные, которые отправляются через протокол HTTP |
| Request body |	Тело запроса, содержащее данные, отправляемые на сервер |
| Response body |	Тело ответа, содержащее данные, возвращаемые сервером |
| Типы данных |	JSON, XML, form-data, text |
| HTTP response statuses |	Коды ответов, которые указывают на статус выполнения запроса: 1xx (информационные), 2xx (успех), 3xx (перенаправление), 4xx (ошибка клиента), 5xx (ошибка сервера) |
| 502 Bad Gateway	| Ошибка, которая возникает, когда сервер не может получить ответ от другого сервера, к которому он обращается |
| 504 Gateway Timeout |	Ошибка, которая возникает, когда сервер не может получить ответ от другого сервера в установленное время |
| HTTP headers |	Информация, передаваемая в заголовках запроса или ответа |
| Authorization	| Заголовок, используемый для передачи токена авторизации от клиента к серверу |
| Cookie / Set-Cookie	| Заголовок, используемый для передачи информации о куки между клиентом и сервером |
| Content-Type |	Заголовок, используемый для указания типа контента, который отправляется или получается через HTTP |
| Content-Encoding |	Заголовок, используемый для указания алгоритма сжатия, используемого для сжатия тела сообщения |
| User-Agent	| Заголовок, используемый для передачи информации о браузере или устройстве, которое отправляет запрос |
| Connection |	Заголовок, используемый для указания параметров соединения между клиентом и сервером |


![Http-versions](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/Http-versions.jpg)

## Client server architecture:

![Простой,клиент-сервер.](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/%D0%A1%D0%B0%D0%BC%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D1%81%D1%82%D0%BE%D0%B9%2C%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80.jpg)

![Клиент - Сервер - БД](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/%D0%A7%D1%83%D1%82%D1%8C%20%D1%81%D0%BB%D0%BE%D0%B6%D0%BD%D0%B5%D0%B5%2C%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%20-%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%20-%20%20%D0%91%D0%94.jpg)

![Много Клиентов - Много Серверов - Много БД](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%20%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B8%D1%85%20%D1%81%D0%B0%D0%B9%D1%82%D0%BE%D0%B2-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B9.jpg)

## OSI-model:

![osi-model](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/OSI.jpg)
