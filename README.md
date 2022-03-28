# Документация по API qr-gid.by

## Получение элемента по ссылке

```
/api/detail/
```

### GET-параметры

```
ID - общий вид параметра имеет ввид RXDXXTLNXXXXX
где:
X - цифра
L - буква
R - область от 1 до 6
D - район - от 1 до 22
T - тип объекта -  S достопримечательность, I - инфраструктура, R - маршрут
N - номер объекта - от 1 до 99999
```

#### Ключи объекта

##### NAME

```
Название объекта
```

##### PREVIEW_TEXT

```
Описание для анонса объекта
```

##### DETAIL_TEXT

```
Детальное описание объекта
```

##### PREVIEW_PICTURE

```
ссылка на картинку для карточки объекта
```

##### PROPERTIES SITE VALUE

```
ссылка на сайт объекта
```

##### PROPERTIES ADDRESS VALUE

```
адрес, по которому находится объект
```

##### PROPERTIES CITY VALUE

```
город, в котором находится объект
```

##### PROPERTIES REGION VALUE

```
область, в которой находится объект
```

##### PROPERTIES AREA VALUE

```
район, в котором находится объект
```

##### PROPERTIES GPS VALUE

```
координаты объекта на карте
```

##### PROPERTIES AUDIOGUIDE VALUE

```
ссылка на аудифайл с гидом по объекту
```

##### PROPERTIES FAX VALUE

```
номер факса для связи с объектом
```

##### PROPERTIES PHONE VALUE #ID#

```
номера телефонов для связи с объектом
```

##### PROPERTIES MAIL VALUE #ID#

```
электронные почты для связи с объектом
```

##### PROPERTIES POSTCODE VALUE

```
почтовый индекс объекта
```

##### PROPERTIES TIME VALUE ID NAME/VALUE

```
вид занятости / время работы объекта
```

##### PROPERTIES WORKING_DAYS VALUE ID #NAME_DAY#

```
дни работы/отдыха (true - работает, false - выходной)
```

##### PROPERTIES TIME MORE_PHOTO VALUE #ID#

```
ссылки на картинки для слайдера
```
