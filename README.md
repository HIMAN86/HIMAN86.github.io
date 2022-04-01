<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Личная карточка</title>
<style>
BODY { background: url(https://f.vividscreen.info/soft/50a4dc4e9b5edc64cb29a008ee06ee5c/Gandalf-Lord-of-the-Rings-Tolkien-2880x1920.jpg)}			}
xyz {display:flex; align:center; color:blue;
font-size:16pt}			
v {background-color:red}
i {color:white}
</style>
<script>
function digitalClock() {
var date = new Date();
var hours = date.getHours();
var minutes = date.getMinutes();
var seconds = date.getSeconds();
//* добавление ведущих нулей */
if (hours < 10) hours = "0" + hours;
if (minutes < 10) minutes = "0" + minutes;
if (seconds < 10) seconds = "0" + seconds;
document.getElementById("id_clock").innerHTML = hours + ":" + minutes + ":" + seconds;
setTimeout("digitalClock()", 1000);																}
 </script>
</head>
<body>
<div id="id_clock"></div>
<script>digitalClock();</script>
<script>
alert("ЗДРАВСТВУЙТЕ");
</script>
<script src="js/main.js"></script>
<div style="text-align:center;"><xyz>
<h1 style="color:red;">Личная карточка</h1>
Доброго времени суток<br>
<v>Я студент 3го курса ЮГУ, группа 2н91б<br></v>
Обучаюсь на нефтегазовом деле<br>
Очень люблю играть в доту, вот картинки моих любимых героев<br>
</xyz></div>
	

<div style="text-align:center;";>
<a href="https://vk.com/gangmemec"><img src="https://avatars.mds.yandex.net/i?id=d577be641c88b29311c1ddd07f1cbe05-5870145-images-thumbs&n=13" height="300px">
</a>
</div>
</body>
</html>
