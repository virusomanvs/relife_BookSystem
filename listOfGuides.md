### Конфиг информации о правилах

| Поле            | Тип      | Описание                                                                 |
| --------------- | -------- | ------------------------------------------------------------------------ |
| `categoryID`    | `string` | Уникальный идентификатор категории                 |
| `guideTitle` | `string` | Ключ для локализации названия. Обычно выглядит как `#STR_...`. Либо прямой перевод |
| `guideIcon`  | `string` | Путь к иконке. Поддерживается формат `.edds`.                  |
| `guideContent`  | `array string` | Массив данных для контента. Может быть картинка, либо просто текст    |

## Пример
### Просто текст
```
"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
```
### Картинка
```
"256|256|relife_BookSystem_Custom/data/places/places/0/0.edds",
```
| Поле            | Тип      | Описание                                                                 |
| --------------- | -------- | ------------------------------------------------------------------------ |
| `256`    | `string` | Ширина в пикселях     |
| `256`    | `string` | Высота в пикселях   |  
| `relife_BookSystem_Custom/data/places/places/0/0.edds`    | `string` | Путь к картинке       |
