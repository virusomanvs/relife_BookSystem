# Параметры объекта "listOfCrafts"

## Структура данных

Объект представляет собой массив рецептов крафта с следующей структурой:

### Основные параметры крафта

| Параметр | Тип | Описание | 
|----------|-----|----------|
| `isShowCraft` | Integer | Показывать ли рецепт в интерфейсе |
| `isAutoShowIngredients` | Integer | Автоматически показывать ингредиенты |
| `categoryID` | String | ID категории крафта, если оставить пустым будет отображено во "Все крафты" |
| `craftItemClassname` | String | Класс создаваемого предмета| 
| `isAutoFindResults` | Integer | Автоматически находить результаты крафта среди всех крафтов RecipeBase |
| `CraftHandleName` | Array[String] | Классы крафта если выключен автоматический поиск крафтов| 
| `NeedPerk` | Integer | Требуемый перк (ID) |
| `needItemInInventory` | Array | Предметы, требуемые в инвентаре | 
| `needItemInInventoryCount` | Array | Количество требуемых предметов | 
| `craftHandleDisplayName` | String | Отображаемое название крафта | 
| `IngredientsOneIcon` | String | Иконка первого ингредиента | 
| `IngredientsTwoIcon` | String | Иконка второго ингредиента | 
| `ignoredCraftToDisplay` | Array[String] | Игнорируемые крафты для отображения | 
| `ingredientsOneList` | Array[String] | Список первых ингредиентов | 
| `ingredientsTwoList` | Array[String] | Список вторых ингредиентов | 

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
