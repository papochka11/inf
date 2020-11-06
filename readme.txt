 (Клонирование проекта в папку nameProject:
 git clone https://... name Project
 
 Добавление файлов в коммит: 
 git add .

 Запись коммита:
 git commit -m "Комментарий коммита"

Отправить коммит:
git push

Принять изменения:
git pull

Авторство коммитов: 
git config --global user.email "ваш емайл"
git config --global user.name "ваше имя"

домашняя работа 

<!DOCTYPE html>
<html>
    <head>
         <style>
         </style>
    </head>
    <body>
         <div class=""></div>

         <script type="text/javascript"></script>
    </body>     
</html>
html>

<head>

<link rel="stylesheet" type="text/css" href="./public/styles/style.css">

</head>

<body id="body">

<div id="time"></div>

<script type="text/javascript" src="./public/scripts/mayn.js">

</script>

</body>

</html>

2

setInterval(() => {

var date = new Date();

var hour = String(((date.getHours()) <10 ? "0" + (date.getHours()) : (date.getHours())));

var min = String((date.getMinutes() < 10 ? "0" + date.getMinutes() : date.getMinutes()));

var sec = String((date.getSeconds() < 10 ? "0" + date.getSeconds() : date.getSeconds()));

var timeColor = '#' + hour + min + sec;

console.log(timeColor);

var time = hour + ":" + min + ":" + sec;

document.getElementById("body").style.backgroundColor = timeColor;

document.getElementById("time").innerText = time;

}, 1000);
body {
background-color: black;
margin: 0;
padding: 0;
}

#time {
text-align: center; color: white:
font-size: 144px;
font-family: Arial;
font-weight: 500;

}
