# VanillaRoulette.js
-------------

`VanillaRoulette.js` - vanilla JavaScript библиотека, предназначенная для горизонтальных поворотов рулеток

## Демонстрация

Вы можете посмотреть демо-версию [здесь](https://extazywowr.a-wow.repl.co) :)

## Использование

Использовать `VanillaRoulette.js` это действительно просто:

 1. **Привяжите** `CSS` и `JS` к своей странице:

```html
<link href="libs/vanillaRoulette/vanillaRoulette.min.css" rel="stylesheet">
<script src="libs/vanillaRoulette/vanillaRoulette.min.js"></script>
```

2. **Создайте** контейнер для рулетки и заполните его блоками контента (вы можете использовать любой тег, заполненный любым контентом):

```html
<div id="roulette">
    <div>...</div>
    <div>...</div>
    <div>...</div>
    <div>...</div>
</div>
```

 3. **Инициализируйте** рулетку (просто передайте уникальный сектор для конструктора `Рулетки`):
 
 ```js
 let roulette = new Roulette("#roulette");
 ```
 
