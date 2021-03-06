
Тестовое задание для компании Монастырев по реализации плагина создания совещаний для redmine

Установка:

1. Перейти в папку redmine/plugins
2. ```git clone https://github.com/fairoj/manage_meetings.git```
3. ``` rake redmine:plugins:migrate ```
4. ``` rake seed:add_venue ``` (для создания тестовых мест проведения совещаний)

Особенности использования:
Для того, что бы создавать совещаний необходимо добавить права для проектных ролей. По умолчанию администратор может добавлять совещаний.

Что еще хотелось бы реализовать:

1. Редактирование совещаний
2. Отображение всех событий в виде редмайновского календаря
3. Просмотр всех совещаний связанных с пользователем или местом проведения
4. Уведомление о предстоящих совещаниях
5. Создание мест проведения совещаний
6. Скрывать элементы создать и удалить совещание от пользователей не имеющих на это прав 

Проблемы с которыми столкунлся в ходе выполнения:

1. Отсутствие нормальной докуметации к redmine, приходилось разбирать исходники
2. Невозможность подгрузки ```select2``` и ```datetimepicker``` в виде гемов
3. Не разобрался до конца с загрузкой файлов, на данный момент невозможно скачать загруженный файл


