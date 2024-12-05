# JavaScript: Основные команды и структуры
## Объявление переменных
- `let`                            # Используется для объявления переменных, которые могут изменяться в будущем, блочная область видимости
- `var`                            # Старый способ объявления переменных, блочная область видимости, не рекомендуется к использованию
- `const`                          # Используется для объявления констант, значение которых нельзя изменить после инициализации

## Функции
- `function`                       # Определение функции
- Пример:
  ```javascript
  function greet(name) {
    console.log("Hello, " + name + "!");
  }
  let name1 = "lice";
  greet(name1);