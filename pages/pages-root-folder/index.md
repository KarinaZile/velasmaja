---
layout: kz-page
header:
  title: ""
  image_fullwidth: main.jpg
permalink: /index.html
homepage: true
widgets:
- image: img1.jpg
- text: "<h3>Laipni lūdzam pašapkalpošanās veļas mazgātavā Speed Queen!</h3><br/>Pie mums var izmazgāt praktiski visu.<br/><h3>Приглашаем вас в прачечную самообслуживания Speed Queen!</h3><br/>У нас можно постирать практически всё."
widgets2:
- image: img2.jpg
- image: img3.jpg
---
<center>
<p style="color:#9D2235">Speed Queen veļas mazgātava Valdeķu ielā uz laiku ir slēgta uz rekonstrukciju. Informatīvais tālrunis: +371 29266564. <br/>
<br/>
Прачечная самообслуживания на Валдекю временно закрыта на реконструкцию. Телефон для информации: +371 29266564.
</p>
</center>

{% include _widget_grid_layout.html widgets=page.widgets articles_per_row=2 %}

{% include _widget_grid_layout.html widgets=page.widgets2 articles_per_row=2 %}
