Конфиг подкатегорий. У каждого раздела могут быть категории, категория "Все" есть всегда.

| Поле            | Тип      | Описание                                                                 |
| --------------- | -------- | ------------------------------------------------------------------------ |
| `categoryID`    | `string` | Уникальный идентификатор категории, использует!                 |
| `categoryTitle` | `string` | Ключ для локализации названия категории. Обычно выглядит как `#STR_...`. Либо прямой перевод |
| `categoryIcon`  | `string` | Путь к иконке категории. Поддерживается формат `.edds`.                  |


## Пример подкатегорий для основных разделов. 
```json
  "Places": [
        {
            "categoryID": "TestCat",
            "categoryTitle": "Toxic Zone Materials",
            "categoryIcon": "relife_Core/images/icons/abstract-001.edds"
        }
    ],
    "Drugs": [
        {
            "categoryID": "TestCat",
            "categoryTitle": "ExampleCat",
            "categoryIcon": "relife_Core/images/icons/abstract-001.edds"
        },
        {
            "categoryID": "TestCat2",
            "categoryTitle": "ExampleCat",
            "categoryIcon": "relife_Core/images/icons/abstract-001.edds"
        }
    ],

```
