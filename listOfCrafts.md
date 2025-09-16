# Параметры объекта "listOfCrafts"

## Структура данных

Объект представляет собой массив рецептов крафта с следующей структурой:

### Основные параметры крафта

| Параметр | Тип | Описание | Обязательный | Значения по умолчанию |
|----------|-----|----------|-------------|---------------------|
| `isShowCraft` | Integer | Показывать ли рецепт в интерфейсе | Да | 1 (true) |
| `isAutoShowIngredients` | Integer | Автоматически показывать ингредиенты | Да | 0 (false) |
| `craftItemClassname` | String | Класс создаваемого предмета | Да | - |
| `isAutoFindResults` | Integer | Автоматически находить результаты крафта | Да | 1 (true) |
| `CraftHandleName` | Array[String] | Названия обработчиков крафта | Да | - |
| `NeedPerk` | Integer | Требуемый перк (ID) | Да | -1 (не требуется) |
| `needItemInInventory` | Array | Предметы, требуемые в инвентаре | Нет | [] |
| `needItemInInventoryCount` | Array | Количество требуемых предметов | Нет | [] |
| `craftHandleDisplayName` | String | Отображаемое название крафта | Нет | "" |
| `IngredientsOneIcon` | String | Иконка первого ингредиента | Нет | "" |
| `IngredientsTwoIcon` | String | Иконка второго ингредиента | Нет | "" |
| `ignoredCraftToDisplay` | Array[String] | Игнорируемые крафты для отображения | Нет | [] |
| `ingredientsOneList` | Array[String] | Список первых ингредиентов | Да | - |
| `ingredientsTwoList` | Array[String] | Список вторых ингредиентов | Да | - |

## Пример использования

```json
{
  "isShowCraft": 1,
  "isAutoShowIngredients": 0,
  "craftItemClassname": "RLF_Ignited_Cigare",
  "isAutoFindResults": 1,
  "CraftHandleName": ["CraftClass"],
  "NeedPerk": -1,
  "needItemInInventory": [],
  "needItemInInventoryCount": [],
  "craftHandleDisplayName": "",
  "IngredientsOneIcon": "",
  "IngredientsTwoIcon": "",
  "ignoredCraftToDisplay": ["craft1", "craft2"],
  "ingredientsOneList": ["Rag"],
  "ingredientsTwoList": ["NailBox"]
}
