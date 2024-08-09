# Rick & Morty

# Ссылки

Дизайн в Figma - [посмотреть](https://tinyurl.com/image-feed-figma)   
API - [посмотреть](https://rickandmortyapi.com/documentation/)    
Скринкаст работы приложения - [посмотреть](https://disk.yandex.ru/i/jWVLphJjx5qh9w)     

# Назначение и цели приложения

iOS-приложение “Персонажи сериала Рик и Морти”. Оно состоит из двух экранов: список персонажей и детальная информация о конкретном персонаже.   
# Цели приложения:

- Просмотр ленты списка персонажей.
- Просмотр краткой информации из профиля персонажа.

# Требования

## Экран со списком персонажей:
- Экран состоит из вертикального списка ячеек с информацией о персонажах,
- Список можно скроллить,
- В ячейке отображаются имя (не больше 1 строки), статус, раса/вид, пол и изображение персонажа,
- При нажатии на ячейку можно перейти к экрану детальной информации,
- Отображаются персонажи первой страницы запроса /character (20 штук).
## Экран детальной информации о персонаже:
- На экране отображаются изображение, имя, статус, раса/вид, пол, список эпизодов, в которых появляется персонаж, и последнее известное местоположение,
- Список эпизодов отображается в формате “1, 4,13”, где числа, это id эпизодов из массива "episode".

# Варианты улучшений для продвинутого уровня (реализовано):
- Добавить на экран списка персонажей пагинацию (при скролле загружается следующая страница) и индикатор загрузки данных (activity indicator),
- На экране детальной информации отображать не id эпизодов, а их названия,
- Добавить иконку приложения и название “Рик и Морти”,
- Добавить экран загрузки приложения (splash screen),
- Добавить отображение ошибки при отсутствии интернета,
- Добавить поиск и/или фильтрацию персонажей (в API есть такая возможность).

