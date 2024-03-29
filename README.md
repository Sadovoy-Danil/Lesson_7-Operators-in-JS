# Lesson_7-Operators-in-JS

### Операторы: 

> сокращенный оператор / смысл

- _**x = y / x = y**_ — присваивает значение правого операнда, левому.

- _**x += y / x = x + y**_ — добавляет значение правого операнда к значению левого, и сохраняет результат в переменную левого операнда.

- _**x -= y / x = x - y**_ — вычитает значение правого операнда из значения левого, и присваивает результат переменной левого операнда.

- _**x * = y / x = x * y**_ — умножает значение правого операнда на значению левого, и сохраняет результат в переменную левого операнда.

- _**x /= y / x = x / y**_ — разделяет значение правого операнда на значения левого, и присваивает результат переменной левого операнда.

- _**x %= y / x = x % y**_ — разделяет значение правого операнда на значения левого, и присваивает долю, которая осталась переменной левого операнда.

> = — присваивание

> == — проверка на равенство

> === — строгая проверка по типам данных

> && — И, || — ИЛИ, ! — знак отрицания

Если перед значением представленым строкой поставить '+', то она претворится в числовой тип данных. Существует префиксная и постфиксная форма инкремнта/декремента. При префиксной форме сначала выполняется операция, а при постфиксной выводит старое значение, а потом уже выполняется операция.

> _var y = ++x; / x = x + 1; var y = x;_

> _var y = ++x; / var y = x; x = x + 1;_

### > [Приоритет операторов](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Operator_Precedence) <

_**Словарь**_

[_Оператор_](https://developer.mozilla.org/ru/docs/Web/JavaScript/Guide/Expressions_and_Operators) — наименьшая автономная часть языка программирования; команда или набор команд.

[_Конкатенация_](https://webformyself.com/vvedenie-v-javascript-konkatenaciya/) — операция склеивания объектов линейной структуры, обычно строк. Например, конкатенация слов «микро» и «мир» даст слово «микромир».

[_Инкремент_](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D0%BA%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D1%82) — операция во многих языках программирования, увеличивающая переменную. 

[_Декремент_](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D0%BA%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D1%82) — обратная операция инкременту.

_**P.S. Фраза 'use strict' означает, что мы пишем скрипт на стандарте ES6**_
