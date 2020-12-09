<!DOCTYPE html>
<html lang="ua">
<head>
<meta charset="utf-8" />
<title>Зоопарк</title>
<head>
 <link rel="shortcut icon" href="/images/favicon.ico" type="image/x-icon">
</head>
</head>
<body>
<!--Создаём таблицу контейнер, которой задаём следующее
оформление:
border="1" - рамка вокруг контейнера. Увеличив число, можно увеличить толщину рамки.
align="center" - размещаем контейнер по центру экрана.
rules="rows" - убираем двойную рамку.
style="width:60%;" - добавляем стилевое свойства, делающее
контейнер и весь сайт "резиновым".
Сделать полноценный адаптивный дизайн, этим способом невозможно.-->
<table
border="1"
align="center"
rules="rows"
style="width:60%;">
<!--Создаём строку-->
<tr>
<!--Создаём ячейку строки-->
<td>
<!--ШАПКА САЙТА-->
<!--В ячейке строки создаём ещё одну таблицу для шапки сайта.
Оформление:
border="1" - двойная рамка толщиной в 1px
background="images/168.png" - картинка в шапке сайта, если требуется.
Адрес картинки вы должны вставить свой.
bgcolor="#7FFFD4" - фоновый цвет в шапке, если нет картинки.
cellpadding="10" - отступ содержимого от рамки не менее 10px.
style="width:100%; border-radius:5px;" - добавляем "резиновость"
и закругляем уголки рамки-->
<table
border="1"
background="images/168.png"
bgcolor="#7FFFD4"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку таблицы-->
<tr>
<!--Создаём столбец таблицы-->
<th>
<!--Содержание ячейки столбца-->
<h1>Зоопарк</h1>
<h3>Сайт севвера зоопарк за основу якого я взяв свій старий код</h3>
<!--Закрываем таблицу-->
</th>
</tr>
</table>

<!--ОСНОВНОЙ КОНТЕНТ-->

<!--В этой же ячейке контейнера создаём ещё одну таблицу
для основного контента.
Оформление как и в предыдущей таблице-->

<table
border="1"
bgcolor="#e6e6fa"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку-->
<tr>
<!--Создаём ячейку
Оформление:
rowspan="2" - объединяем две ячейки в одну.
Число объединяемых ячеек по числу ячеек в сайдбаре.
style="width:80%" - основной контент занимает 80% всей площади,
оставшиеся 20% для сайдбара-->
<td
rowspan="2"
style="width:80%">
<h2>Про наш сервер</h2>
<!--Начинаем абзац с красной строки-->
<p style="text-indent:20px">
На нашому сервері проходять конкурси, ми завжди
додаємо щось нове, є своє телебачення (майже своє)
дУжЕ дРуЖеЛюбНе КоМьЮнІтІ... Приєднюйся!</p>

<p style="text-indent:20px">ибими лох.</p>
<!--Закрываем ячейку-->
</td>

<!--САЙДБАР-->

<!--Создаём ячейку сайдбара-->
<td bgcolor="#e6e6fa">
<h3>Посилання:</h3>
<!--Абзац для ссылки на страницу сайта-->
<p>
<!--Ссылка на страницу сайта-->
<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&list=PLneRaqXoYlV10RUsU6uP-6cicVmwr0g2O&index=400">
<!--Картинка маркера перед названием страницы-->
<img src="http://trueimages.ru/img/00/06/f4fffdb5.png">
<!--Название страницы
style="margin-left:5px;" - отступ названия от маркера-->
<span style="margin-left:5px;">Точно не рікрол</span></a>
<!--Закрываем абзац-->
</p>
<p>
<a href="https://discord.gg/wE8mtxv6Ea">
<img src="http://trueimages.ru/img/31/ab/4dcb087c2ae4305edcd15171696.jpg">
<span style="margin-left:5px;">Ссилка на сервер</span;></a>
</p>
<p>
<a href="https://pustoproject.com/">
<img src="http://trueimages.ru/img/31/ab/4dcb087c2ae4305edcd15171696.jpg">
<span style="margin-left:5px;">Пусто</span></a>
</p>
<!--Закрываем строку Меню-->
</td>
</tr>
<!--Создаём строку с дополнительной информацией-->
<tr>
<!--Ячейка с дополнительной информацией-->
<td
bgcolor="#e6e6fa"
align="center">
<h3>Інфа про сервер</h3>
<p>4 бота, 12 учасників</p>
<!--Закрываем ячейку с общей информацией
и таблицу основного контента-->
</td>
</tr>
</table>

<!--Ибими лох-->

<!--Создаём таблицу подвала-->
<table
border="1"
bgcolor="#7FFFD4"
height="100"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку.-->
<tr>
<!--Создаём столбец-->
<th>
<h3>Тут пусто. Що додати сюда, підкажіть в #advices</h3>
<!--Закрываем таблицу подвала. При желании в подвале можно
сделать несколько строк и столбцов-->
</th>
</tr>
</table>
<!--Закрываем таблицу контейнера-->
<iframe src="https://discord.com/widget?id=745001051286929561&theme=dark" width="350" height="500" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
</td>
</tr>
</table>
</body>
</html>