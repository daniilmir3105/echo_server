# Echo-server
## Задание: 
Напишите программу для Linux, представляющую собой эхо-сервер. Этот
сервер принимает соединения на заданном порту и на каждую принятую порцию
данных отправляет в ответ эту же порцию данных. Данные могут быть любой
последовательностью байт. Протокол взаимодействия — TCP/IPv4.

## Краткое описание реализованного решения:

1) Реализован простой TCP-сервер, который принимает от клиента строку (порциями по 1 КБ) и возвращает ее. (Эхо-сервер).
2) Сервер выводит в консоль служебные сообщения (с пояснениями) при наступлении любых событий:
  * Запуск сервера;
  * Начало прослушивания порта;
  * Подключение клиента;
  * Прием данных от клиента;
  * Отправка данных клиенту;
  * Отключение клиента;
  * Остановка сервера.
3) Данный TCP-клиент, который устанавливает соединение с сервером, считывает строку со стандартного ввода и посылает его серверу.
4) Клиент должен выводить в консоль служебные сообщения (с пояснениями) при наступлении любых событий:
  * Соединение с сервером;
  * Разрыв соединения с сервером;
  * Отправка данных серверу;
  * Прием данных от сервера.
