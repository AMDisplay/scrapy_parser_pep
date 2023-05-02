# Scrapy Parse Pep

## Описание проекта

Парсинг и запись Pep документов в csv файл

## Установка и использование

### Скопировать репозиторий, активировать вирт. окружение, установить зависимости

git clone git@github.com:AMDisplay/scrapy_parser_pep.git

python -m venv venv

python -m pip install --upgrade pip

pip install -r requirements.txt

### Запуск парсинга

scrapy crawl pep

### Хранение данных

Данные записываются и хранятся в двух таблицах формата csv
Таблица pep имеет атрибуты number,name,status - номер Pep, название, статус
Таблица status_summary имеет атрибуты status, count - Статус и количество pep