# Справочник технологий и практик

# Build process.
1. Проверяем версию, чистим её (clean)
2. Нажмаем verify
3. Ждем, идем за кофе
4. Находим баг, плачем и сетуем на судьбу
5. Находим источник бага - правим
6. Загружаем изменения через build-run
7. Тестируем 
8. Рассказываем маме о своем успехе
# Pull request with GitHub
1. Вытягиваем свежую версию с GitHub 
2. Создаем New Pull request на вкладке Pull requests -> Merge
3. Вливаем свежую версию изменений себе (shift + shift -> pull)
4. Вносим необходимые нам изменения -> Commit (Ctrl+K)
5. Радуемся жизни (нет)

## Фреймворки
Набор готового функционала от сторонних разработчиков в виде модулей или библиотек, готовый для переиспользования в разных проектах.
В отличие от библиотек, которые входят в часть программы, фреймворк вызывает код разработчика.
Аналогия: фреймворк - квартира, библиотека - это стол (его можно переиспользовать).

Примеры фреймворков:
JAVA - Spring
Python - Django
JavaScript - Vue.js, Angular, React

Примеры библиотек:
WinApi - библиотека вызова системных функций на уровне ОС
math.cpp - библиотека математических функций для C++ 

## Типовая архитектура

FrontEnd: JavaScript, Angular, React, Vue
BackEnd: Java

Форматы обмена данных: XML, JSON, Binary

## Logical structure
Layers:
controller 'отвечает за выбор метода,журнолирование,безопастность. Отвечает на вопрос: сюда ли ты пришел?
service    'компоненты,которые несут бизнес логику, по факту = user story
domain     'объекты, которые моделируют предметную область. Наш класс
dao        '= репозиторий.Это класс,который содержит внутри себя логику работы с БД
