<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: 'Times New Roman', Times, serif;">
    <p align = "center" style="font-size: 14;">
        МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ <br>
        РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
        ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
        ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
        «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»<br>
    </p>
    <br><br><br><br><br><br>
    <body font-size = "12">
        <p align = "center"> 
            Институт естественных наук и техносферной безопасности<br>
            Кафедра информатики<br>
            Бахтина Елена Владимировна<br>
        </p>
        <br><br><br>
        <p align = "center">
            <strong>Лабораторная работа №3. «HTML»</strong><br>
            01.03.02 Прикладная математика и информатика
        </p>
        <br><br><br><br><br><br><br><br><br><br><br><br>
        <p align = "right"> 
            Научный руководитель<br>
            Соболев Евгений Игоревич
        </p>
        <br><br><br>
        <p align = "center">г. Южно-Сахалинск<br>2022 г.</p>
    </body>
    <body style="font-family: 'Times New Roman', Times, serif;">
        <h2 align = "center">Введение</h2>
        <p font-size = "12">
            <b>HTML</b> (от англ. HyperText Markup Language — «язык гипертекстовой разметки») — стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере.
            Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.
        </p>
        <br>
        <h2 align = "center">Цель и задачи</h2>
        <p align = "left" font-size = "12"> 
            Цель: создать страницу на HTML.<br>
            Задачи:<br>
                1. Создать все виды заголовков с текстом "Hello world" c классом "heading". <!--<h1>Hello world</h1>--><br>
                2. Каждому заголовку также дать id (к прим. heading-1, heading-2...)<br> 
                3. Задать всем заголовкам цвет текста на красный<br> 
                4. Второму заголовку синий<br> 
                5. Третьему заголовку поменять задний фон на чёрный<br> 
                6. Четвертому заголовку сделать border и округлить углы<br> 
                7. Пятому заголовку создать :hover эффект (любой)<br> 
                8. Создайте 6 input с разными типами.<br> 
                9. Создать нумерованный список из 4 элементов с текстом “Нумерованный”.<br> 
                10. Создать маркированный список из 4 элементов с текстом “Маркированный” и квадратным маркером.<br> 
                11. Создайте веб-страницу с зеленым фоном и белым текстом из 30 слов.<br> 
                12. Создать 6 блоков с нумерацией и такими параметрами (ширина 100px и высота 100px, зеленого цвета , внешним отступом 10px). Их родительским элементом должен быть container.<br> 
                13. Поставить все блоки по центру страницы.<br> 
                14. Добавьте тэг <!--<iframe>--> на вашу страницу.<br>
                15. Сделайте простую форму регистрации на сайте (Только верстка).<br>
                16. Сделайте таблицу на странице.<br>
                17.Создайте стиль для заголовка h1 с красным цветом текста.<br>
                18. Установите шрифт Arial для всех параграфов на странице.<br>
                19. Добавьте тень на блок div с помощью свойства box-shadow.<br>
                20. Установите фоновый цвет #f0f0f0 для всего документа.<br>
                21. Создайте анимацию, которая будет мигать красным цветом.<br>
                22. Установите отступы внутри блока div с помощью свойства padding.<br>
                23. Создайте стиль для ссылок, которые будут менять цвет при наведении на них курсора.<br>
                24. Добавьте границу вокруг изображения с помощью свойства border.<br>
                25. Создайте стиль для списка ul с маркерами в виде квадратов.<br>
                26. Установите ширину и высоту блока div с помощью свойств width и height.<br>
                27. Создайте стиль для таблицы, который будет делать каждую вторую строку серой.<br>
                28. Добавьте эффект перехода при наведении на кнопку с помощью свойства transition.<br>
                29. Установите фоновое изображение для элемента с помощью свойства background-image.<br>
                30. Создайте стиль для формы с полями для ввода текста и кнопкой отправки.<br>
                31. Добавьте рамку вокруг текстового поля с помощью свойства outline.<br>
                32. Установите выравнивание текста по центру в блоке div с помощью свойства text-align.<br>
                33. Создайте стиль для выпадающего меню с помощью псевдоэлемента :hover.<br>
                34. Добавьте тень на текст с помощью свойства text-shadow.<br>
                35. Создайте стиль для анимации появления элемента на странице с помощью свойства opacity.<br>
                36. Установите шрифт размером 18 пикселей для всех заголовков на странице.<br>
        </p>
        <h2 align = "center">Решение</h2>
        <p font-size = "12">Для выполнения этой лабораторной работы, я пользовался:</p>
        <p> 1.  Материалом в сети интернет</p>
        </body>
    <h3 align = "center">Файл laba3.html</h3>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>laba3</title>
    <link rel="stylesheet" href="style.css">
</head>
<body1>
    <h1 class="heading" id="h-1">Hello world</h1>
    <h2 class="heading" id="h-2">Hello world</h2>
    <h3 class="heading" id="h-3">Hello world</h3>
    <h4 class="heading" id="h-4">Hello world</h4>
    <h5 class="heading" id="h-5">Hello world</h5>
    <h6 class="heading" id="h-6">Hello world</h6>
</body1>
<body>
    <input type="text">
    <input type="number" style="width: 30px;">
    <input type="button" value="жопа">
    <input type="checkbox" style="height: 100px; width: 100px;">
    <input type="color">
    <input type="password" maxlength="12" title="password">
    <ol>
        <li style="list-style-type: none;">Нумерованный</li> <li value="1">Петров</li> <li>Сидоров</li> <li>Николаев</li> <li>Николаев</li>
    </ol>
    <ul style="list-style-type: square;">
        <li style="list-style-type: none;">Маркированный</li> <li>Красный</li> <li>Желтый</li> <li>Зеленый</li> <li>Синий</li> <li>Синий</li>
    </ul>
    <br>
    <a href="laba3_1.html" target="_blank">Следующее задание</a>
</body>
</html>
```
<h3 align = "center">Файл laba3_1.html</h3>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>laba3_1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(121, 167, 75); color: aliceblue;">
    <p>1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30</p>
    <div class="container">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
        <div>666</div>
    </div>
    <iframe src="https://kotiko.ru/vopros-otvet/7-prichin-pochemu-kot-lizhet-svoi-jajca.html"height="960px" width="800px"></iframe>
    <br>
    <a href="laba3_2.html" target="_blank">Следующее задание</a>
</body>
</html>
```
<h3 align = "center">Файл laba3_2.html</h3>

```
<!DOCTYPE html>
<html lang="en" style="    
    margin-top: 15px;
    margin-left: 100px;
    margin-bottom: 5px;
    margin-right: 100px;
    background-color: #f0f0f0;">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>laba3_2</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>
    <h3 style="padding-left: 68px; margin-left: 41%">Регистрация</h3>
    <div id="div1">
        <form>
            <p>Имя <input type="text" required placeholder="Имя"></p>
            <p>Фамилия <input type="text" required placeholder="Фамилия"></p>
            <p>Телефон <br><input style="outline: auto; outline-color: palevioletred;" type="text" required placeholder="+7-900-000-00-00"></p>
            <input type="reset"> <input type="submit" style="margin-left: 22px">
        </form>
    </div>
    <script>
        document.addEventListener('submit', function () {alert('aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa')})
    </script>
    <div id="general">
        <div id="div2">
            <table class="tbl1">
                <tr id="tr1">
                    <th><img src="https://i.pinimg.com/564x/3a/f1/04/3af104a979f14c8c37c05adacd1b82c8.jpg" alt="ладно" width="100" height="100"></th>
                    <th><img src="https://i.pinimg.com/564x/3a/f1/04/3af104a979f14c8c37c05adacd1b82c8.jpg" alt="ладно" width="100" height="100"></th>
                </tr>
                <tr>
                    <td><img src="https://i.pinimg.com/564x/0a/9e/ae/0a9eaed127a8876e62117f7169c846f3.jpg" alt="ладно" width="100" height="100"></td>
                    <td><img src="https://i.pinimg.com/564x/0a/9e/ae/0a9eaed127a8876e62117f7169c846f3.jpg" alt="ладно" width="100" height="100"></td>
                </tr>
                <tr>
                    <td><img src="https://i.pinimg.com/564x/0a/9e/ae/0a9eaed127a8876e62117f7169c846f3.jpg" alt="ладно" width="100" height="100"></td>
                    <td><img src="https://i.pinimg.com/564x/0a/9e/ae/0a9eaed127a8876e62117f7169c846f3.jpg" alt="ладно" width="100" height="100"></td>
                </tr>
            </table>
        </div>
        <div id="div3">
            <a href="https://lichess.org/ru" target="_blank">нажмите пожалуйста</a><br>
            <img id="img1" src="https://i.pinimg.com/564x/71/d4/55/71d455b35d5f5f13aeaf4492a37e6231.jpg" alt="обезяна">
        </div>
    </div>
    <div id="general1">
        <div id="div4">
            <ul>
                <li>1</li>
                <li>2</li>
                <li>3</li>
            </ul>
        </div>
        <div id="div_pup"></div>
        <div id="div5">
            <input class="btn1" type="button" value="OK">
        </div>
        <div class="dropdown">
            <button class="dropbtn">Менюшечка</button>
            <div class="dropdown-content">
              <a href="#">заказать трактор</a>
              <a href="#">попить кофе</a>
              <a href="#">поиграть</a>
            </div>
          </div>
    </div>
</body>   
</html>
```
<h3 align = "center">Файл style.css</h3>

```
.heading{font-family: 'Times New Roman', Times, serif; color: red;}
        #h-2{color: blue;}
        #h-3{background-color: black;}
        #h-4{border: 1px solid black; border-radius: 12px;}
.container{padding-left: 50%;}  
        div{width: 100px; height: 100px; color: green; padding: 10px;}
```
<h3 align = "center">Файл style1.css</h3>

```
@keyframes changeColor
{
    0% {border: 7px solid grey;}
    100% {border: 7px solid rgb(236, 92, 116);}
}
@keyframes buttonfun 
{
    0% {scale: 50%;}
    100% {scale: 110%;}    
}
@keyframes buttonendfun 
{
    100% {scale: 110%; color: #ffffff;}
    0% {scale: 50%; background-color: rgb(248, 3, 44); transform: scale(200%);}    
}
@keyframes display_blocks 
{
    0% { 
        opacity: 0; 
        display: none; 
    } 
  
    50% { 
        opacity: 0.5; 
        display: inline-block; 
    } 
  
    100% { 
        opacity: 1; 
        display: block; 
    }     
}
.tbl1
{
    animation-name: changeColor;
    animation-duration: 1s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
    animation-timing-function: linear;
}
/*tr:nth-child(even){background-color: grey;}*/
#div1
{
    width: 211px;
    border: 5px solid rgb(194, 55, 141); border-radius: 10px; 
    background-color: rgba(245, 121, 245, 0.801);
    padding-top: 10px; padding-right: 10px; padding-bottom: 25px; padding-left: 10px;
    margin-left: 41%;
    box-shadow: 15px 15px 10px 1px grey;
    text-align: center;
}
#general
{
    height: 350px;
    width: 1000px;
    padding-top: 20px;
}
#general1
{
    height: 150px;
    width: 1500px;
    padding-top: 20px;
}
#div2
{
    padding-left: 5%;
    float: left;
}
#div3
{
    float: right;
    padding-right: 70px;
}
#div4
{
    width: 250px; height: 200px;
    padding-left: 5%;
    padding-top: 1%;
    background-image: url("https://img.razrisyika.ru/kart/27/1200/107258-malenkie-kotiki-33.jpg");
    background-size: contain;
    float: left;
}
#div_pup {width: 460px; height: 200px; float: left;}
#div5
{
    float: left;
    padding-bottom: 150px;
    padding-right: 175px;
    width: 200px;
}
table{border-collapse: collapse;}
h1{color: red;}
p{font-family: Arial;}
a{font-size: 24px; color: rgb(255, 255, 255); padding-left: 15px;}
a:hover{color: rgb(253, 6, 233); transition: color 2s;}
ul
{
    list-style: square;
    font-size: 20px;
    color: white;
}
#img1
{
    border: 4px solid rgb(236, 92, 116);
    border-radius: 5%;
}
.btn1
{
    animation-name: buttonendfun;
    animation-duration: 60ms;
    animation-iteration-count: initial;
    animation-direction: alternate;
    animation-timing-function: linear;
}
.btn1:hover
{
    background-color: rgb(248, 3, 44);
    transform: scale(200%);   
    transition: background-color 2s, transform 1s;
    animation-name: buttonfun;
    animation-duration: 70ms;
    animation-iteration-count: infinite;
    animation-direction: alternate;
    animation-timing-function: linear;
}

.dropbtn {
    background-color: rgba(245, 121, 245, 0.801);
    border: 2px solid rgb(194, 55, 141); border-radius: 10px; 
    color: white; text-shadow: 5px 1px 2px rgb(0, 0, 0);
    padding: 16px;
    font-size: 16px;
  }
  
.dropdown {
    position: relative;
    display: inline-block;
  }
  
.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
  }
.dropdown-content a {
    color: black;
    padding: 12px 16px;
    font-size: 14px;
    text-decoration: none;
    display: block;
  }
.dropdown-content a:hover {background-color: #ddd;}
.dropdown:hover .dropdown-content 
{
    display: block;
    animation-name: display_blocks;
    animation-duration: 2s;
    animation-iteration-count: initial;
    animation-direction: alternate;
    animation-timing-function: linear;
}
.dropdown:hover .dropbtn {background-color: rgb(253, 6, 233);}
h1,h2,h3,h4,h5,h6{font-size: 18px;}
```
<br>
 <h2 align = "center">Вывод</h2>
 <p align = "left" font-size = "12">
    По итогу данной лабороторной работы, я научилась создавать создавать таблицы, анимации, фреймы и применять стили 😊   
</p>
</body>
</html>
