#### Книга: PostgreSQL 16 под капотом: архитектура и методы оптимизации Author https://aristov.tech
#### Для демонстрации внутреннего устройства создана уникальная БД по пассажирским автобусным перевозкам в Тайланде
#### Основано на реальных городах, маршруты, расстояниях и +-стоимости
#### Инструкция по скачиванию и заливке: 
#### Объем порядка 6 млн.строк (600МБ):
#### wget https://storage.googleapis.com/thaibus/thai_small.tar.gz && tar -xf thai_small.tar.gz && psql < thai.sql
#### Объем порядка 60 млн.строк (6Гб):
#### wget https://storage.googleapis.com/thaibus/thai_medium.tar.gz && tar -xf thai_medium.tar.gz && psql < thai.sql
#### Объем порядка 600 млн.строк (60Гб):
#### wget https://storage.googleapis.com/thaibus/thai_big.tar.gz && tar -xf thai_big.tar.gz && psql < thai.sql
#### База открыта и доступна для любых обучающих проектов со ссылкой на этот источник
#### Схема БД:
![Схема Thai booking](https://github.com/aeuge/postgres16book/blob/main/database/thai_book.png)
