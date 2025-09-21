Конфиг категорий для крафтов

| Поле            | Тип      | Описание                                                                 |
| --------------- | -------- | ------------------------------------------------------------------------ |
| `categoryID`    | `string` | Уникальный идентификатор категории, который указывается в конфиге крафта!                 |
| `categoryTitle` | `string` | Ключ для локализации названия категории. Обычно выглядит как `#STR_...`. Либо прямой перевод |
| `categoryIcon`  | `string` | Путь к иконке категории. Поддерживается формат `.edds`.                  |

```
 "listOfCraftCategories": [
        {
            "categoryID": "Cannabis",
            "categoryTitle": "Cannabis",
            "categoryIcon": "relife_BookSystem/images/craft.edds"
        },
        {
            "categoryID": "Other",
            "categoryTitle": "Other",
            "categoryIcon": "relife_BookSystem/images/craft.edds"
        }
    ],
```
