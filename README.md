# BookStore
Написать WebApi-приложение — магазин книг. Условия:
- Приложение
- .NET Core 3.1 и выше
- получение данных через API, без UI
- Swagger
- структурированная иерархия папок
- База данных
- использование EF Core вместе с подходом Code-First (миграции)
- cущности - книга, заказ
- взаимодействие с данными через паттерн Repository
- MSSQL или MySQL
- Функционал
- получение списка книг по фильтру (название, дата выхода)
- получение полной информации по ID книги
- сохранение заказа
- Один заказ - несколько книг
- получение списка заказов по фильтру (номер, дата заказа)
- Компоненты, библиотеки
- минимум один middleware (общий вид обработки исключений)
- разделение между Entity и Models (можно использовать Mapper)
- Приветствуется
- написание summary
- написание комментариев
