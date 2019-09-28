Back-end приложения NoQueue (команда .pluxury?, стол №11)

API:

http://demo142.delta.vkhackathon.com/api/v1/malls

метод для получения списка торговых центров, может принимать параметры вида `?lat={coordinate}&?lnt={coordinate}`.
Если параметры переданы, список трц будет отсортирован в порядке от самого ближнего к самому дальнему. Координаты трц хранятся в бд.


http://demo142.delta.vkhackathon.com/api/v1/malls/1

метод для получения детальной информации о трц, и работающих на фудкорте кафе. У каждого кафе есть список доступных товаров и категорий.


http://demo142.delta.vkhackathon.com/api/v1/cafes

метод для получения списка доступных кафе, с категориями товаров, которыми они продают.


http://demo142.delta.vkhackathon.com/api/v1/cafes/1

метод для получения подробной информации о кафе, содержит список заказов и список доступных товаров.


http://demo142.delta.vkhackathon.com/api/v1/orders/1

метод для получения подробной информации по заказу