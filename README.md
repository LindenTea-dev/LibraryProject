# ООП приложение с консольным меню

## Предметная область
Библиотека. Реализован упрощенный процесс взятия книги в аренду и ее возврат

## Хранение данных
- JSON-файл
- TXT-файл


## Категории классов
Классы разбиты по папкам в соответсвии с их функционалом
| № | Папка | Назначение классов | Ссылки |
|---|---|---|---|
| 1 | Data | Модели данных |  |
| 2 | Handler | Управление моделями данных приложения | Data |
| 3 | Service | Логика, не связанная с интерфейсом приложения | Data, Handler |
| 4 | UnitTest | Тестирование приложения | Data |
