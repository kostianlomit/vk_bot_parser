# Vk_bot_parser

Данный бот собирает данные со стены в vk
Парсер vk написан на библеотеках request, bs4 обращение к vk через API vk
База данных используется postrgess, ORM - SQLAlchemy

При запуске бота (/start) бот нначинает сбор данных со стенны группы в vk,
затем по команде /items (/photo) выдает фотографии нужной группы.

Можно сохранить фотографии в БД (/photo), либо выдавать напрямую через парсер (/items)
 
