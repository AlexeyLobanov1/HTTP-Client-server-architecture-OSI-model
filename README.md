# HTTP, Client server architecture, OSI-model

#### HTTP:

| Термин | Описание |
| :----------------- | :------------------ |
| HTTP | Hypertext Transfer Protocol, an application layer protocol for exchanging data between two links in a network |
| Протокол |	A set of rules and conventions for exchanging data between two or more devices on a network |
| HTTP methods | Methods that define the type of request used to exchange data between two links in the system: GET, POST, PUT, PATCH, DELETE, OPTIONS |
| OPTIONS	| A method used to request information about available HTTP methods on the server |
| HTTP body	| Data that is sent via the HTTP protocol |
| Request body |	Request body containing data sent to the server |
| Response body |	The body of the response containing the data returned by the server |
| Типы данных |	JSON, XML, form-data, text |
| HTTP response statuses |	Response codes that indicate the status of the request: 1xx (informational), 2xx (success), 3xx (redirection), 4xx (client error), 5xx (server error) |
| 502 Bad Gateway	| The error that occurs when the server cannot receive a response from the other server to which it is accessing |
| 504 Gateway Timeout |	Error that occurs when the server cannot receive a response from another server at the set time |
| HTTP headers |	Information transmitted in the headers of the request or response |
| Authorization	| Header used to transfer the authorization token from the client to the server |
| Cookie / Set-Cookie	| Header used to transfer cookie information between the client and the server |
| Content-Type |	The header used to specify the type of content that is sent or received via HTTP |
| Content-Encoding |	Header used to specify the compression algorithm used to compress the message body |
| User-Agent	| The header used to convey information about the browser or device that sends the request |
| Connection |	Header used to specify the connection parameters between the client and the server |


![Http-versions](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/Http-versions.jpg)

## Client server architecture:

![Простой,клиент-сервер.](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/%D0%A1%D0%B0%D0%BC%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D1%81%D1%82%D0%BE%D0%B9%2C%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80.jpg)

![Клиент - Сервер - БД](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/%D0%A7%D1%83%D1%82%D1%8C%20%D1%81%D0%BB%D0%BE%D0%B6%D0%BD%D0%B5%D0%B5%2C%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%20-%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%20-%20%20%D0%91%D0%94.jpg)

![Много Клиентов - Много Серверов - Много БД](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%20%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B8%D1%85%20%D1%81%D0%B0%D0%B9%D1%82%D0%BE%D0%B2-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B9.jpg)

## OSI-model:

![osi-model](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/OSI.jpg)
