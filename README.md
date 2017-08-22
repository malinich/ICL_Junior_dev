# Junior dev
#### Коммиксы marvel

> Компания дистрибьютор "Stark Inc" поставляет своему заказчику Falcon & Hulk список комиксов, которые она распространяет с разрешения Marvel. Сейчас "Stark Inc" ведет свой учет в exel таблицах, а это очень неудобно. Тони Старк решил модернизировать свою компанию.
Он хочет иметь возможность получать комиксы от Marvel (используя Marvel Comics API) не посещая сам сайт Marvel и выборочно сохранять результаты к себе.

_UseCase_:
- Заказчик заходит на страницу /marvel/ , на странице будет форма с поиском.
- Заказчик набирает нужный ему заголовок комикса и получает список найденных комиксов (название, дата выхода, EAN, варианты выхода, обложка) .
- Заказчик нажимает на нужный ему комикс и получает всю информацию о комиксе (название, описание, дата выхода, все связанные картинки, список персонажей в выпуске и stories)
- Заказчик сохраняет этот комикс

_UseCase2_
- Заказчик заходит на страницу /master/ и получает все комиксы которые он сохранил ранее
- Заказчик может отрыть комикс, получить полную информацию о данном комиксе, может удалить комикс, изменить его, скрыть его от пользователей.

_UseCase3:_
- Пользователь заходит на страницу /comics/ и получает список комиксов которые заказчик предлагает ему.

использовать:
- python
- django
- django rest framework
- angular2
