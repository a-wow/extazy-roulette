# VanillaRoulette.js
-------------

`VanillaRoulette.js` - vanilla JavaScript библиотека, предназначенная для горизонтальных поворотов рулеток

## Демонстрация

Вы можете посмотреть демо-версию [здесь](https://kir-antipov.github.io/VanillaRoulette/sample/index.html) :)

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
 
  4. **Профит**

<br>
  
`VanillaRoulette` имеет ряд настраиваемых опций, so you're welcome to visit our [Wiki](https://github.com/Kir-Antipov/VanillaRoulette/wiki)!)
