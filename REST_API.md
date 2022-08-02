# **REST api**

REST api - cпособ взаимодействия клиента с сервером, с помощью HTTP запросов.

## REST правила

- Запросы должны идентифицировать ресурсы. Это происходит за счет единого идентификатора ресурсов.

- Клиенты имеют достаточно информации в представлении ресурса, чтобы при желании изменить или удалить ресурс. Сервер выполняет это условие, отправляя метаданные, которые дополнительно описывают ресурс.

- Клиенты получают информацию о дальнейшей обработке представлений. Сервер реализует это, отправляя описательные сообщения, где содержатся метаданные о том, как клиент может использовать их оптимальным образом.

- Клиенты получают информацию обо всех связанных ресурсах, необходимых для выполнения задачи. Сервер реализует это, отправляя гиперссылки в представлении, чтобы клиенты могли динамически обнаруживать больше ресурсов.

## RESTful

Сервис написанный с использование всех правил REST принято называть RESTful

## Методы HTTP в REST api

- GET - получить объект.

- POST - создать новый объект (передать какие-нибудь данные).

- PUT - изменить объект целиком.

- PATCH - изменить отдельные поля объекта.

- DELETE - удалить объект, если он существует.