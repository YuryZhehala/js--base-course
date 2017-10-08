## Домашнее задание
 
###  Прочитать* (с выполнением задач) разделы из учебника [Learn.Javascript.Ru](http://learn.javascript.ru/):
- [Автоматические тесты при помощи chai и mocha](https://learn.javascript.ru/testing)
- [Отладка в браузере Chrome](https://learn.javascript.ru/debugging-chrome)
- [Методы объектов и контекст вызова](https://learn.javascript.ru/objects-more)
- [setTimeout и setInterval](https://learn.javascript.ru/settimeout-setinterval)
- [Документ, события, интерфейсы](https://learn.javascript.ru/ui)

### Найти ответы на вопросы (это то, что будет спрашиваться на занятии):
- Что такое контекст вызова функции? Чем определяется?
- Как изменить `this` внутри функции? (5 способов)
- чем различаются `.call` / `.apply` / `.bind`
- Что такое сигнатура функции?
- Чем характеризуется функция?
- Что такое прототип?
- Как работает конструктор? Что происходит при вызове со словом `new` ?
- Как происходит чтение свойств из объекта?
- Как происходит запись свойств в объект?
- Как проверить на принадлежность классу?
- Как работает `instanceof` ?
- 4е принципа ООП
- виды полиморфизма. И их объяснение
- событийный цикл в javascript
- что такое фаза захвата / capturing ?
- что такое фаза всплытия / bubbling ?
- как подписаться на событие документа / html элемента?
- что такое `Функция высшего порядка`?
- что такое синхронный / асинхронный код?
- что такое `каррирование` ?
- в чем разница объявления методов в конструкторе и на `.prototype` ?
- что такое 'полифилл'?

### Решить задачи (подробнее см 02/ht/example/script.js)
 - `isDeepEqual` (добавлены тесты) 
 - написать ФВП (функцию высшего порядка) `bind` 
 - написать методы `.myBind` (именно с таким названием)
 - создать объект с волшебным свойством
 - создать конструктор для работы с цепочками вызовов
 - написать фукнцию калькулятор
 - написать синглтон
 - написать конктруктор, который  всегд конструктор
 - написать сумматор
 - написать и покрыть тестами каррирующую функцию
 - создать цепочку наследования
 - создать форму и ее обработчик
 - создать генератор листаемого календаря

---
 - Написать реализацию функций [debounce](http://underscorejs.ru/#debounce) и [throttle](http://underscorejs.ru/#throttle)  и покрыть реализации тестами ( Если ваше имя начинается с гласной  - `debounce`, иначе - `throttle`. А лучше - обе ). Функции должны с сигнатурой `debounce(fun, delay)` / `throttle(fun, delay)`
 - К генератору листаемого календаря добавить функционал: под календарем добавить блок. При клике на ячейку даты ( но не на пустую ячейку календаря ) в блоке должна добавляться запись о том, по какой ячейке кликнули. Можно добавить запрос описания даты от пользователя ( с помощью функции `prompt` и выводить это описание там же). История дат и список,  по которым пользоатель клика, должны сохраняться между перезагрузками страницы. Для сохранения использовать [LocalStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage). Интерфейс работы с данными (чтение/запись) лучше сделать асинхронным
 - Создать синхронную функцию `sleep(seconds)` так, чтобы работал код
 ```javascript
 console.log(new Date()); // Sun Oct 08 2017 10:44:34 GMT+0300 (+03)
 sleep(9);
 console.log(new Date()); // Sun Oct 08 2017 10:44:43 GMT+0300 (+03)
```

 
## Видео
 - [https://www.youtube.com/watch?v=8cV4ZvHXQL4](https://www.youtube.com/watch?v=8cV4ZvHXQL4)
 - [https://learn.javascript.ru/screencast/gulp](https://learn.javascript.ru/screencast/gulp)