<!DOCTYPE html>
<html lang="ua">
<head>
<title>Page Title</title>
<meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <title>Mini Calendar / Date Picker</title>
  <link rel="stylesheet" href="css/style.css">
  <!--[if lt IE 9]><script src="//html5shim.googlecode.com/svn/trunk/html5.js"></script><![endif]-->
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
    box-sizing: border-box;
}

/* Стиль тіла  сторінки*/
body {
    font-family: Arial;
    margin: 0;
}

/* Заголовок/Логотип/Назва */
.header {
    padding: 80px;
    text-align: center;
    background: 	#008000;
    color: white;
}

/* Збільшіть розмір шрифту заголовка */
.header h1 {
    font-size: 40px;
}

/* Стилізуйте верхню панель навігації */
.navbar {
    overflow: hidden;
    background-color: 	#808000;
}
/* Стилізуйет посилання на панелі навігації */
.navbar a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
}

/* Посилання, вирівняне по правому краю */
.navbar a.right {
    float: right;
}

/* Змінити колір при наведенні курсора */
.navbar a:hover {
    background-color: #ddd;
    color: black;
}

/* Колонний контейнер */
.row {  
    display: -ms-flexbox; /* IE10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE10 */
    flex-wrap: wrap;
}

/* Створіть два нерівних стовпці, які сидять один біля одного */
/* Бічна панель/ліва колонка */
.side {
    -ms-flex: 30%; /* IE10 */
    flex: 30%;
    background-color: #f1f1f1;
    padding: 20px;
}
/* Основна колонка */
.main {   
    -ms-flex: 70%; /* IE10 */
    flex: 70%;
    background-color: white;
    padding: 20px;
}

/* Фальшиве зображення, тільки для цього прикладу */
.fakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 20px;
}

/* Нижній колонтитул */
.footer {
    padding: 20px;
    text-align: center;
    background: #ddd;
}

/* Адаптивний макет – коли ширина екрана менше 700 пікселів, накладіть два стовпці один на одного, а не поруч. */
@media screen and (max-width: 700px) {
    .row {   
        flex-direction: column;
    }
}

/* Адаптивний макет – коли екран має ширину менше 400 пікселів, накладайте навігаційні посилання один на одного, а не поруч. */
@media screen and (max-width: 400px) {
    .navbar a {
        float: none;
        width: 100%;
    }
}
</style>
</head>
<body>

<div class="header">
  <h1> Мій веб-сайт </h1>
  <p> Сайт, створений мною.</p>
</div>

<div class="navbar">
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#" class="right">Link</a>
</div>
<div class="row">
  <div class="side">
      <h2>Про мене</h2>
      <img src="picture.jpg">
      <div class="fakeimg" style="height:200px;">Image</div>
      <p> Я</p>
      <h3> Я Назар мені 13 наразі у мюнхені</h3>
      <p>Опис тексту до зображень.</p>
      <div class="fakeimg" style="height:60px;">Image</div><br>
      <div class="fakeimg" style="height:60px;">Image</div><br>
      <div class="fakeimg" style="height:60px;">Image</div>
  </div>
  <div class="main">
      <h2>Назва Заголовка </h2>
      <h5> Опис заголовка, Листопад 15, 2023</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>текст.</p>
      <p>текст
<img src="picture.jpg">
 <section class="container">
    <div class="cal">
      <table class="cal-table">
        <caption class="cal-caption">
          <a href="index.html" class="prev">&laquo;</a>
          <a href="index.html" class="next">&raquo;</a>
          May 2012
        </caption>
        <tbody class="cal-body">
          <tr>
            <td class="cal-off"><a href="index.html">30</a></td>
            <td><a href="index.html">1</a></td>
            <td><a href="index.html">2</a></td>
            <td class="cal-today"><a href="index.html">3</a></td>
            <td><a href="index.html">4</a></td>
            <td><a href="index.html">5</a></td>
            <td><a href="index.html">6</a></td>
          </tr>
          <tr>
            <td><a href="index.html">7</a></td>
            <td class="cal-selected"><a href="index.html">8</a></td>
            <td><a href="index.html">9</a></td>
            <td><a href="index.html">10</a></td>
            <td><a href="index.html">11</a></td>
            <td class="cal-check"><a href="index.html">12</a></td>
            <td><a href="index.html">13</a></td>
          </tr>
          <tr>
            <td><a href="index.html">14</a></td>
            <td><a href="index.html">15</a></td>
            <td><a href="index.html">16</a></td>
            <td class="cal-check"><a href="index.html">17</a></td>
            <td><a href="index.html">18</a></td>
            <td><a href="index.html">19</a></td>
            <td><a href="index.html">20</a></td>
          </tr>
          <tr>
            <td><a href="index.html">21</a></td>
            <td><a href="index.html">22</a></td>
            <td><a href="index.html">23</a></td>
            <td><a href="index.html">24</a></td>
            <td><a href="index.html">25</a></td>
            <td><a href="index.html">26</a></td>
            <td><a href="index.html">27</a></td>
          </tr>
          <tr>
            <td><a href="index.html">28</a></td>
            <td><a href="index.html">29</a></td>
            <td><a href="index.html">30</a></td>
            <td><a href="index.html">31</a></td>
            <td class="cal-off"><a href="index.html">1</a></td>
            <td class="cal-off"><a href="index.html">2</a></td>
            <td class="cal-off"><a href="index.html">3</a></td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <section class="about">
    <p class="about-links">
      <a href="http://www.cssflow.com/snippets/mini-calendar-date-picker" target="_parent">View Article</a>
      <a href="http://www.cssflow.com/snippets/mini-calendar-date-picker.zip" target="_parent">Download</a>
    </p>
    <p class="about-author">
      &copy; 2023&ndash;2013 <a href="http://thibaut.me" target="_blank">Thibaut Courouble</a> -
      <a href="http://www.cssflow.com/mit-license" target="_blank">MIT License</a><br>
      Original PSD by <a href="http://dribbble.com/shots/240129-Calender" target="_blank">James McDonald</a>
    </p>
  </section>

 <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <title>Check Buttons</title>
  <link rel="stylesheet" href="css/style.css">
  <!--[if lt IE 9]><script src="//html5shim.googlecode.com/svn/trunk/html5.js"></script><![endif]-->

</body>
</html>
