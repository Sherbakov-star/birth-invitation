<script>

</script>
<template>
<!-- <div id="header">
			<div class="content">
				<ul>
					<li><a href="">self22</a></li>
					<li><a href="">смысл</a></li>
					<li><a href="">результаты</a></li>
					<li><a href="">гарантии</a></li>
					<li><a href="">цена</a></li>
				</ul>
			</div>
</div> -->

<!-- <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Приглашение на день рождения</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="invitation">
        <h1>Приглашение на день рождения</h1>
        <p>Дорогой друг/подруга!</p>
        <p>Приглашаю тебя на мой день рождения, который состоится:</p>
        <p><strong>Дата:</strong> DD.MM.YYYY</p>
        <p><strong>Время:</strong> HH:MM</p>
        <p><strong>Место:</strong> Адрес проведения</p>
        <p>Мы будем рады видеть тебя на нашем празднике! Пожалуйста, подтверди свое присутствие.</p>
        <p>С наилучшими пожеланиями,<br>Имя/Фамилия</p>
    </div>
</body> -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birthday Invitation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>День Рождения</h1>
        <p>Приглашаем вас отметить мой день рождения!</p>
        <p>Дата: 10 января</p>
        <p>Время: 19:00</p>
        <p>Место: Ресторан "Party Time"</p>
    </div>
</body>

</template>
<style>
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline}
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}
html{height:100%}
body{line-height:1}
ol,ul{list-style:none}
blockquote,q{quotes:none}
blockquote:before,blockquote:after,q:before,q:after{content:'';content:none}
table{border-collapse:collapse;border-spacing:0}

/* body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

.invitation {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color: #ffffff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    text-align: center;
    color: #333333;
}

p {
    margin-bottom: 10px;
    line-height: 1.5;
    color: #666666;
}

strong {
    font-weight: bold;
    color: #333333;
} */

/* @keyframes wipe-enter {
  0% {
    transform: scale(0, .025);
  }
  50% {
    transform: scale(1, .025);
  }
}

@media (prefers-reduced-motion: no-preference) {
  .square {
    animation-name: wipe-enter;
    animation-duration: 1s;
    animation-iteration-count: infinite;
  }
} */

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    text-align: center;
}

.container {
    max-width: 600px;
    margin: 0 auto;
    background-color: #ffffff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    color: #333333;
}

p {
    color: #666666;
    line-height: 1.5;
}

/* Анимация */
@keyframes fadeIn {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}

.container {
    animation: fadeIn 1s ease-in-out;
}

/* Адаптация для мобильных устройств */
@media only screen and (max-width: 600px) {
    .container {
        max-width: 100%;
        padding: 10px;
    }
}
</style>