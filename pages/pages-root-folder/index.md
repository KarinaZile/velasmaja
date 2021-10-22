---
layout: kz-page
header:
  title: ""
  image_fullwidth: main.jpg
permalink: /index.html
homepage: true
widgets:
- image: img1.jpg
- text: "<h3>Laipni lūdzam pašapkalpošanās veļas mazgātavā Speed Queen!</h3><br/>Pie mums var izmazgāt praktiski visu.<br/><h3>Приглашаем вас в прачечную самообслуживания Speed Queen!</h3><br/>У нас можно постирать практически все."
widgets2:
- image: img2.jpg
- image: img3.jpg
---

{% include _widget_grid_layout.html widgets=page.widgets articles_per_row=2 %}

{% include _widget_grid_layout.html widgets=page.widgets2 articles_per_row=2 %}
