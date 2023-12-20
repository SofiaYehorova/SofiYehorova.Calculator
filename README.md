<!DOCTYPE html>
<html lang="ua">
<head>
<meta charset="UTF-8">
<title>Відсоткові калькулятор</title>
<style type="text/css">
a{
color: #00BFFF;
text-decoration: none;
}
html{
background: #F0F8FF;
min-height: 100%;
font-family: Helvetica;
display: flex;
flex-direction: column;
}
body{
margin: 0;
padding: 0 15px;
background:"istockphoto-481003125-612x612.jpg";
display: flex;
flex-direction: column;
flex: auto;
}
h1{
margin-top: 0;
}
h1, p{
color: #006064;
}
.header{
width: 100%;
min-width: 460px;
max-width: 960px;
margin: 0 auto 30px;
padding: 30px 0 10px;
display: flex;
flex-wrap: wrap;
justify-content: space-between;
box-sizing: border-box;
}
.logo{
font-size: 1.5rem;
color: #00BFFF;
text-decoration: none;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
display: flex;
flex: none;
align-items: center;
background: #F0F8FF;
width: 130px;
height: 50px;
}
.nav{
margin: -5px 0 0 -5px;
display: flex;
flex-wrap: wrap;
}
.nav-item{
background:#F0F8FF;
width: 130px;
height: 50px;
font-size: 1.5rem;
color: #00BFFF;
text-decoration: none;
display: flex;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
}
.sqr{
height: 300px;
width: 300px;
background: #F0F8FF;
}
.main{
width: 100%;
min-width: 460px;
max-width: 960px;
margin: auto;
flex: auto;
box-sizing: border-box;
}
.box{
font-size: 1.25rem;
line-height: 1.5;
margin: 0 0 40px -50px;
display: flex;
flex-wrap: wrap;
justify-content: center;
}
.box-base{
margin-left: 50px;
flex: 1 0 430px;
}
.box-side{
margin-left: 50px;
font: none;
}
.content{
margin-bottom: 30px;
display: flex;
flex-wrap: wrap;
}
.banners{
flex: 1 1 200px;
}
.banner{
background: #F0F8FF;
width: 100%;
min-width: 100px;
min-height: 200px;
font-size: 3rem;
color: #00BFFF;
margin: 0 0 30px 0;
display: flex;
justify-content: center;
align-items: center;
}
.posts{
margin: 0 0 30px 30px;
flex: 1 1 200px;
}
.comments{
margin: 0 0 15px 15px;
flex: 1 1 100px;
}
.comment{
display: flex;
}
.comment-side{
padding-right: 10px;
flex: none;
}
.comment-base{
flex: auto;
}
.comment-avatar{
background: #F0FFFF;
width: 50px;
height: 50px;
}
@media screen and  (max-width: 800px) {
.banners{
margin-left: -30px;
display: flex;
flex-basis: 100%;
}
.banner{
margin-left: 10px;
}
.posts{
margin-left: 0;
}
}
@media screen and  (max-width: 600px) {
.content{
display: block;
}
.banners{
margin: 0;
display: block;
}
.banner{
margin-left: 0;
}
.posts{
margin: 0;
}
}
</style>
</head>
<body>
<header class="header">
<a class="logo">
LOGO
</a>
<nav class="nav">
<a href="#posts" class="nav-item">Опис</a>
<a href="#comments" class="nav-item">Тема</a>
<a href="#posts" class="nav-item">Відсотки</a>
</nav>

</header>
<main class="main">
<div class="box">
<div class="box-base">
<h1>Загальний опис. Актуальність відсоткового калькулятору</h1>
<p>Економічна теорія з використанням відсотків визначає основні засади функціонування фінансово-економічних систем та їх взаємодію з різними суб'єктами. Відсоткові ставки виступають ключовим елементом цієї теорії, оскільки вони впливають на різні аспекти економіки, включаючи інвестиції, споживчі витрати, рівень кредитування та інші.</p>
</div>
<div class="box-side">
<div class="sqr">

</div>
</div>
</div>
<div class="content">
<div class="banners">
<div class="banner">Баннер 1</div>
<div class="banner">Баннер 2</div>
<div class="banner">Баннер 3</div>
</div>
<div class="posts"  id="posts">
<div class="post">
<h1>Опис</h1>
<h1>Чому потрібні та для чого відсоткові калькулятори в економіці</h1>
<p>Відсоткові калькулятори в економіці є важливим інструментом для розрахунків і визначення різних фінансових параметрів.</p>
</div>
<div class="post">
<h1>Відсотки в економіці</h1>
<p>Ось декілька сфер, де вони використовуються:</p>
<p>Розрахунок відсотків: відсоткові калькулятори дозволяють легко визначити обсяг відсотків від певної суми грошей. Наприклад, вони можуть бути використані для розрахунку відсотків на кредит, депозит чи інші фінансові інструменти.</p>
<p>Кредитні операції: при оцінці вартості кредиту важливо враховувати не лише процентну ставку, але і період позички та кількість платежів. Відсоткові калькулятори допомагають визначити суму щомісячних чи річних платежів і загальний обсяг виплат.</p>
<p>Дисконтні розрахунки: в бізнесі відсоткові калькулятори використовуються для розрахунку дисконтованих потоків грошей. Це дозволяє визначити сучасну вартість майбутніх грошових потоків та оцінити проект чи інвестицію.</p>
<p>Депозитні операції: якщо ви маєте гроші на депозиті, ви можете використовувати відсотковий калькулятор для розрахунку очікуваних виплат за вкладом в залежності від різних умов та відсоткових ставок.</p>
  <p>Розрахунок прибутку та збитків: відсоткові калькулятори також можуть бути використані для оцінки прибутку чи збитків від фінансових операцій чи інвестицій.</p>
  <p>Облік відсотків по кредиту: коли ви виплачуєте кредит, частина суми йде на сплату відсотків, а решта - на сплату основної суми кредиту. Відсоткові калькулятори допомагають розрахувати, яка частина платежу призначена на відсотки, а яка - на основну суму кредиту.</p>
  <p>Використання відсоткових калькуляторів спрощує фінансові розрахунки, допомагає у прийнятті раціональних рішень та визначенні фінансової ефективності різних операцій чи інвестицій.</p>
</div>
<div class="post">
<h1>Концепцій економічної теорії</h1>
<p>Однією з фундаментальних концепцій економічної теорії є часова цінність грошей. Вона визначає, що гроші, одержані чи витрачені сьогодні, мають іншу вартість, ніж ті самі гроші в майбутньому. Ця ідея є в основі розуміння ролі відсотків у економіці.</p>
<p>Формула для розрахунку майбутньої вартості (FV) грошей включає в себе відсоткову ставку (r) та період часу (t):</p>
  <center><img src="Італія.jpeg" width="50%"/></center>
</div>
</div>
<div class="comments"  id="comments">
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #1</h1>
<p>Рекламный бриф масштабирует из ряда вон выходящий выставочный стенд. Изменение глобальной стратегии, в рамках сегодняшних воззрений, индуцирует культурный ребрендинг.</p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #2</h1>
<p>Имидж предприятия, в рамках сегодняшних воззрений, вполне вероятен. Стоит отметить, что имидж версифицирован. Экспертиза выполненного проекта осмысленно программирует из ряда вон выходящий клиентский спрос. </p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Комментарий #3</h1>
<p>Представляется логичным, что особенность рекламы нейтрализует потребительский сегмент рынка. Изменение глобальной стратегии редко соответствует рыночным ожиданиям. </p>
</div>
</div>

</main>
</body>
</html>
