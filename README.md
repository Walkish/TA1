# Тестовое задание:

На основании данных мы хотим считать следующий набор метрик:

* Количество показов и уникальных пользователей за день в разрезе по платформам, в том числе по всем платформам суммарно;
* Количество за день уникальных авторов и уникального контента, показанного в ленте;
* Количество сессий, средняя глубина просмотра (по позиции фида) и средняя продолжительность пользовательской сессии в ленте за день.

Напишите алгоритмы / запросы для их расчета.

Если это необходимо – допускается создание промежуточных объектов.

### Описание данных
Данные по показам в ленте. Одна строчка – показ одного «фида» в ленте.

Фидом называем один логический элемент
Описание полей:

* durationMs – время в течение которого пользователь видел фид
* position – позиция в ленте на которой был показан фид
* owners – создатели контента в фиде
* resources – ссылки на ID контента, содержащегося в фиде