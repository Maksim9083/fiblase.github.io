<!DOCTYPE html>
<html lang="en" class="no-js">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge"> 
		<meta name="viewport" content="width=device-width, initial-scale=1"> 
		<title>Tab Styles Inspiration</title>
		<meta name="description" content="Tab Styles Inspiration: A small collection of styles for tabs" />
		<meta name="keywords" content="tabs, inspiration, web design, css, modern, effects, svg" />
		<meta name="author" content="Codrops" />
        <style>


@font-face {
	font-family: "Swiss721BT-Black";
	src: url("fonts/swiss721bt-black.eot"); /* IE 9 Compatibility Mode */
	src: url("fonts/swiss721bt-black.eot?#iefix") format("embedded-opentype"), /* IE < 9 */
		url("fonts/swiss721bt-black.woff2") format("woff2"), /* Super Modern Browsers */
		url("fonts/swiss721bt-black.woff") format("woff"), /* Firefox >= 3.6, any other modern browser */
		url("fonts/swiss721bt-black.ttf") format("truetype"), /* Safari, Android, iOS */
		url("fonts/swiss721bt-black.svg#swiss721bt-black") format("svg"); /* Chrome < 4, Legacy iOS */
}

body {
  font-family: "Swiss721BT-Black", "Arial";
  -webkit-transform: translateZ(0);
  -ms-transform: translateZ(0);
  transform: translateZ(0);
}
.periodic {
  position: relative;
  height: 200px;
  margin-right: -1px;
  text-shadow: none;
}
.periodic-row {
  clear: both;
  height: 10%;
}
.cell {
  float: left;
  position: relative;
  width: 5.55%;
  height: 100%;
}
.element {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 1px;
  right: 1px;
  box-sizing: border-box;
  box-shadow: 0px 0px 4px rgba(255, 255, 255, 0.5);
  border: 1px solid rgba(0, 0, 0, 0.05);
  text-align: center;
  cursor: default;
  pointer-events: none;
  -webkit-transition: all 200ms ease;
  transition: all 200ms ease;
  background-color: rgba(0, 128, 128, 0.8);
}
.cell:hover .element {
  border-color: rgba(0, 0, 0, 0.1);
  -webkit-transform: scale(3, 3);
  -ms-transform: scale(3, 3);
  transform: scale(3, 3);
  z-index: 1;
  background-color: rgba(0, 128, 128, 0.9);
}
.at_num,
.at_details {
  position: absolute;
  font-size: 4px;
  color: rgba(255, 255, 255, 0.5);
  opacity: 0;
}
.at_num {
  top: 4px;
  left: 5px;
}
.symbol {
  position: absolute;
  top: 50%;
  left: 0px;
  right: 0px;
  margin-top: -4px;
  font-size: 9px;
  line-height: 1;
  height: 9px;
  color: rgba(255, 255, 255, 0.9);
}
.at_details {
  bottom: 4px;
  left: 0px;
  right: 0px;
}
.cell:nth-child(-n+2) .element,
.cell:nth-child(n+13) .element {
  background-color: rgba(0, 160, 96, 0.6);
}
.cell:nth-child(1) .element,
.periodic-row:nth-child(2) .cell:nth-child(n+14) .element,
.periodic-row:nth-child(3) .cell:nth-child(n+15) .element,
.periodic-row:nth-child(4) .cell:nth-child(n+16) .element,
.periodic-row:nth-child(5) .cell:nth-child(n+17) .element {
  background-color: rgba(0, 192, 64, 0.6);
}
.periodic-row:nth-child(-n+6) .cell:nth-child(18) .element {
  background-color: rgba(64, 192, 0, 0.6);
}
.periodic-row:nth-child(n+9) .element {
  background-color: rgba(0, 96, 160, 0.6);
}
.cell:nth-child(-n+2):hover .element,
.cell:nth-child(n+13):hover .element {
  background-color: rgba(0, 160, 96, 0.9);
}
.cell:nth-child(1):hover .element,
.periodic-row:nth-child(2) .cell:nth-child(n+14):hover .element,
.periodic-row:nth-child(3) .cell:nth-child(n+15):hover .element,
.periodic-row:nth-child(4) .cell:nth-child(n+16):hover .element,
.periodic-row:nth-child(5) .cell:nth-child(n+17):hover .element {
  background-color: rgba(0, 192, 64, 0.9);
}
.periodic-row:nth-child(-n+6) .cell:nth-child(18):hover .element {
  background-color: rgba(64, 192, 0, 0.9);
}
.periodic-row:nth-child(n+9) .cell:hover .element {
  background-color: rgba(0, 96, 160, 0.9);
}
.cell:nth-child(1) .element {
  -webkit-transform-origin: 0 50%;
  -ms-transform-origin: 0 50%;
  transform-origin: 0 50%;
}
.cell:nth-child(18) .element {
  -webkit-transform-origin: 100% 50%;
  -ms-transform-origin: 100% 50%;
  transform-origin: 100% 50%;
}
.periodic-row:nth-child(10) .cell .element {
  -webkit-transform-origin: 50% 100%;
  -ms-transform-origin: 50% 100%;
  transform-origin: 50% 100%;
}
.periodic-row:nth-child(1) .cell:nth-child(1) .element {
  -webkit-transform-origin: 0 0;
  -ms-transform-origin: 0 0;
  transform-origin: 0 0;
}
.periodic-row:nth-child(1) .cell:nth-child(18) .element {
  -webkit-transform-origin: 100% 0;
  -ms-transform-origin: 100% 0;
  transform-origin: 100% 0;
}
.periodic-row:nth-child(10) .cell:nth-child(18) .element {
  -webkit-transform-origin: 100% 100%;
  -ms-transform-origin: 100% 100%;
  transform-origin: 100% 100%;
}
@media (min-width: 600px) {
  .periodic {
    height: 460px;
    margin-right: -2px;
  }
  .element {
    right: 2px;
    bottom: 2px;
  }
  .at_num,
  .at_details {
    font-size: 4px;
    opacity: 1;
  }
  .symbol {
    margin-top: -17px;
    font-size: 16px;
    font-weight: bold;
    line-height: 30px;
    height: 30px;
    color: rgba(255, 255, 255, 0.75);
    text-shadow: 0 0 4px rgba(255, 255, 255, 0.5);
  }
}
@media (min-width: 800px) {
  .periodic {
    height: 540px;
  }
  .symbol {
    font-size: 20px;
  }
}
@media (min-width: 992px) {
  .periodic {
    height: 680px;
  }
  .at_num,
  .at_details {
    font-size: 7px;
  }
  .symbol {
    font-size: 24px;
  }
}
@media (min-width: 1200px) {
  .periodic {
    height: 800px;
  }
  .at_num {
    font-size: 14px;
  }

  .at_details {
    font-size: 9px;
  }
  .symbol {
    font-size: 30px;
  }
}

            
@import url(http://fonts.googleapis.com/css?family=Raleway:400,500,700);

@font-face {
	font-weight: normal;
	font-style: normal;
	font-family: 'codropsicons';
	src:url('../fonts/codropsicons/codropsicons.eot');
	src:url('../fonts/codropsicons/codropsicons.eot?#iefix') format('embedded-opentype'),
		url('../fonts/codropsicons/codropsicons.woff') format('woff'),
		url('../fonts/codropsicons/codropsicons.ttf') format('truetype'),
		url('../fonts/codropsicons/codropsicons.svg#codropsicons') format('svg');
}

*, *:after, *:before { -webkit-box-sizing: border-box; box-sizing: border-box; }

body {
    background-color: transparent;
	color: #74777b;
	font-weight: 400;
	font-size: 1em;
	font-family: 'Raleway', Arial, sans-serif;
}

a {
	color: #2CC185;
	text-decoration: none;
	outline: none;
}

a:hover, a:focus {
	color: #74777b;
}

.hidden {
	position: absolute;
	width: 0;
	height: 0;
	overflow: hidden;
	opacity: 0;
}

.container > section {
	padding: 5em 0;
	font-size: 1.25em;
	min-height: 100%;
    background-color: transparent;
}

p {
	text-align: center;
	padding: 1em;
}

@media screen and (max-width: 30em) {
	.container > section {
		padding: 3em 0;
	}
}


nav,section{display:block;}html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%;}body{margin:0;}a:focus{outline:thin dotted;}a:active,a:hover{outline:0;}img{border:0;}svg:not(:root){overflow:hidden;}

@font-face {
	font-weight: normal;
	font-style: normal;
	font-family: 'stroke7pixeden';
	src:url('../fonts/stroke7pixeden/stroke7pixeden.eot?u58ytb');
	src:url('../fonts/stroke7pixeden/stroke7pixeden.eot?#iefixu58ytb') format('embedded-opentype'),
		url('../fonts/stroke7pixeden/stroke7pixeden.woff?u58ytb') format('woff'),
		url('../fonts/stroke7pixeden/stroke7pixeden.ttf?u58ytb') format('truetype'),
		url('../fonts/stroke7pixeden/stroke7pixeden.svg?u58ytb#stroke7pixeden') format('svg');
}

.tabs {
	position: relative;
	overflow: hidden;
	margin: 0 auto;
	width: 100%;
	font-weight: 300;
	font-size: 1.25em;
}

.tabs nav {
	text-align: center;
}

.tabs nav ul {
	position: relative;
	display: -ms-flexbox;
	display: -webkit-flex;
	display: -moz-flex;
	display: -ms-flex;
	display: flex;
	margin: 0 auto;
	padding: 0;
	max-width: 1500px;
	list-style: none;
	-ms-box-orient: horizontal;
	-ms-box-pack: center;
	-webkit-flex-flow: row wrap;
	-moz-flex-flow: row wrap;
	-ms-flex-flow: row wrap;
	flex-flow: row wrap;
	-webkit-justify-content: center;
	-moz-justify-content: center;
	-ms-justify-content: center;
	justify-content: center;
}

.tabs nav ul li {
	position: relative;
	z-index: 1;
	display: block;
	margin: 0;
	text-align: center;
	-webkit-flex: 1;
	-moz-flex: 1;
	-ms-flex: 1;
	flex: 1;
}

.tabs nav a {
	position: relative;
	display: block;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
	line-height: 2.5;
}

.tabs nav a span {
	vertical-align: middle;
	font-size: 0.75em;
}

.tabs nav li.tab-current a {
	color: #74777b;
}

.tabs nav a:focus {
	outline: none;
}

.content-wrap {
	position: relative;
}

.content-wrap section {
	display: none;
	margin: 0 auto;
	padding: 1em;
	max-width: 1500px;
	text-align: center;
}

.content-wrap section.content-current {
	display: block;
}

.content-wrap section p {
	margin: 0;
	padding: 2em 0;
	color: rgba(0, 0, 0, 1);
	font-weight: 900;
	font-size: 1em;
	line-height: 1.5;
}

@media screen and (max-width: 58em) {
	.tabs nav a:before {
		margin-right: 0;
	}
}
*/

.tabs-style-shape {
	max-width: 1500px;
}

.tabs-style-shape nav ul li {
	margin: 0 3em;
}

.tabs-style-shape nav ul li:first-child {
	margin-left: 0;
}

.tabs-style-shape nav ul li.tab-current {
	z-index: 100;
}

.tabs-style-shape nav li a {
	overflow: visible;
	margin: 0 -3em 0 0;
	padding: 0;
	color: #fff;
	font-weight: 500;
}

.tabs-style-shape nav li:first-child a span {
	padding-left: 2em;
	border-radius: 30px 0 0 0;
}

.tabs-style-shape nav li:last-child a span {
	padding-right: 2em;
	border-radius: 0 30px 0 0;
}

.tabs-style-shape nav li a svg {
	position: absolute;
	left: 100%;
	margin: 0;
	width: 3em;
	height: 100%;
	fill: #bdc2c9;
}

.tabs-style-shape nav li a svg:nth-child(2),
.tabs-style-shape nav li:last-child a svg {
	right: 100%;
	left: auto;
	-webkit-transform: scale3d(-1,1,1);
	transform: scale3d(-1,1,1);
}

.tabs-style-shape nav li a span {
	display: block;
	overflow: hidden;
	padding: 0.65em 0;
	background-color: #bdc2c9;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.tabs-style-shape nav li a:hover span {
	background-color: #2CC185;
}

.tabs-style-shape nav li a:hover svg {
	fill: #2CC185;
}

/* Make only shape clickable */
.tabs-style-shape nav li a svg {
	pointer-events: none;
}

.tabs-style-shape nav li a svg use {
	pointer-events: auto;
}

.tabs-style-shape nav li.tab-current a span,
.tabs-style-shape nav li.tab-current a svg {
	-webkit-transition: none;
	transition: none;
}

.tabs-style-shape nav li.tab-current a span {
	background: #fff;
}

.tabs-style-shape nav li.tab-current a svg {
	fill: #fff;
}

.tabs-style-shape .content-wrap {
	background: #fff;
}

@media screen and (max-width: 58em) {
	.tabs-style-shape nav ul {
		display: block;
		padding-top: 1.5em;
	}
	.tabs-style-shape nav ul li {
		display: block;
		margin: -1.25em 0 0;
		-webkit-flex: none;
		flex: none;
	}
	.tabs-style-shape nav ul li a {
		margin: 0;
	}
	.tabs-style-shape nav ul li svg {
		display: none;
	}
	.tabs-style-shape nav ul li a span {
		padding: 1.25em 0 2em !important;
		border-radius: 30px 30px 0 0 !important;
		box-shadow: 0 -1px 2px rgba(0,0,0,0.1);
		line-height: 1;
	}
	.tabs-style-shape nav ul li:last-child a span {
		padding: 1.25em 0 !important;
	}
	.tabs-style-shape nav ul li.tab-current {
		z-index: 1;
	}
}

.content-wrap section {
    display: none;
}

.content-wrap section:first-child {
    display: block;
}


.kurkov-img {
  margin-top: 7%;
  
}

.kurkov-text {
  margin-top: 13%;
}

.mendeleev {
  width: 250%;
  margin-top: 60%;
}

.warpper {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.tab {
  cursor: pointer;
  padding: 10px 20px;
  margin: 0px 2px;
  background: #32557f;
  display: inline-block;
  color: #fff;
  border-radius: 3px 3px 0px 0px;
  box-shadow: 0 0.5rem 0.8rem #00000080;
}

.panels {
  background: #fff;
  box-shadow: 0 2rem 2rem #00000080;
  min-height: 500px;
  width: 100%;
  max-width: 900px;
  border-radius: 3px;
  overflow: hidden;
  padding: 20px;
}

.panel {
  display: none;
  animation: fadein 0.8s;
}

@keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

.panel-title {
  font-size: 1.5em;
  font-weight: bold;
}

.radio {
  display: none;
}

#one:checked ~ .panels #one-panel,
#two:checked ~ .panels #two-panel,
#three:checked ~ .panels #three-panel {
  display: block;
}

#one:checked ~ .tabs #one-tab,
#two:checked ~ .tabs #two-tab,
#three:checked ~ .tabs #three-tab {
  background: #fff;
  color: #000;
  border-top: 3px solid #32557f;
}

.silica-Nd-1 {
  width: 50%;
  margin-top: 2%;
}

.silica-Nd-2 {
  width: 50%;
  margin-top: 3.5%;
}

.silica-Nd-text {
  padding-top: 40%;
  font-size: 1em;
}

.silica-Yb-text {
  padding-top: 5%;
  font-size: 1em;
}

.silica-Yb-1 {
  width: 50%;
  margin-top: 2%;
}

.silica-Tm-text {
  padding-top: 5%;
  font-size: 1em;
}

.silica-Tm-1 {
  width: 50%;
  margin-top: 2%;
}

.season_tabs {
  position: relative;   
  min-height: 500px; /* This part sucks */
  clear: both;
  margin: 25px 0;
}
.season_tab {
  float: left;  
  clear: both;
  width: 286px;
}
.season_tab label {
    background: #eee;
    padding: 10px;
    border: 1px solid #ccc;
    margin-left: -1px;
    font-size: 21px;
    vertical-align: middle;
    position: relative;
    left: 1px;
    width: 264px;
    height: 68px;
    display: table-cell;
}
.season_tab [type=radio] {
  display: none;   
}
.season_content {
  position: absolute;
  top: 0;
  left: 286px;
  background: white;
  right: 0;
  bottom: 0;
  padding: 20px;
  border: 1px solid #ccc;
 }
.season_content span {
  animation: 0.5s ease-out 0s 1 slideInFromTop; 
}
[type=radio]:checked ~ label {
  background: white;
  border-bottom: 2px solid #8bc34a;
  z-index: 2;
}
[type=radio]:checked ~ label ~ .season_content {
  z-index: 1;
}

.mid-ir-Tb-1 {
  width: 60%;
  margin-top: 4%;
}

.mid-ir-Tb-text {
  font-size: 1em;
  color: #000;
  margin-top: 5%;
}
.mid-ir-Dy-1 {
  width: 60%;
  margin-top: 4%;
}

.mid-ir-Dy-text {
  font-size: 1em;
  color: #000;
  margin-top: 5%;
}
.mid-ir-Ce-1 {
  width: 35%;
  margin-top: 4%;
}
.mid-ir-Ce-2 {
  width: 60%;
  margin-top: 0.5%;
}

.mid-ir-Ce-text {
  font-size: 1em;
  color: #000;
  margin-top: 5%;
}

.periodic-table-text {
  width: 580%;
  margin-top: 30%;
}

.periodic {
  width: 80%;
  margin-top: 17%;
  margin-left: 1%;
}
#clock-container {
    margin-left: 1%;
    margin-top: 10%;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}
#clock {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    box-shadow: 0px 0px 3px rgba(0, 0, 0, 0.9);
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #1c2731;
    background: linear-gradient(170deg, rgba(49, 57, 73, 0.8) 20%, rgba(49, 57, 73, 0.5) 20%, rgba(49, 57, 73, 0.5) 35%, rgba(41, 48, 61, 0.6) 35%, rgba(41, 48, 61, 0.8) 45%, rgba(31, 36, 46, 0.5) 45%, rgba(31, 36, 46, 0.8) 75%, rgba(49, 57, 73, 0.5) 75%), linear-gradient(45deg, rgba(20, 24, 31, 0.8) 0%, rgba(41, 48, 61, 0.8) 50%, rgba(82, 95, 122, 0.8) 50%, rgba(133, 146, 173, 0.8) 100%) #313949;
}
#clock span {
    position: absolute;
    transform: rotate(calc(30deg * var(--i)));
    inset: 8px;
    text-align: center;
}
#clock span i {
    transform: rotate(calc(-30deg * var(--j)));
    display: inline-block;
    font-size: 20px;
    font-style: normal;
    text-shadow: 1px 1px 0px rgb(0 0 0 / 25%);
    color: #ffffff;
}
#clock::after {
    content: '';
    position: absolute;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background-color: #fff;
    z-index: 2;
    opacity: 0.6;
}
#clock .hand {
    position: absolute;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
#clock .hand i {
    position: absolute;
    background-color: var(--color);
    width: var(--width);
    height: var(--height);
    border-radius: 8px;
}
.container-2 {
  display: flex;
  align-items: flex-start; /* выравнивание по верхнему краю */
}

#clock-container {
  margin-top: 30%;
  margin-left: 2%;
  margin-right: 1%; /* отступ справа от часов до таблицы */
}
.podlojka-img {
  width: 75%;
  position: absolute;
}
        </style>
        <script>
            document.addEventListener("DOMContentLoaded", function () {
    const tabs = document.querySelectorAll(".tabs nav ul li a");
    const contents = document.querySelectorAll(".content-wrap section");

    // Функция, которая показывает активный контент и скрывает неактивный
    function showContent(tabIndex) {
        contents.forEach((content, index) => {
            content.style.display = (index === tabIndex) ? "block" : "none";
        });

        tabs.forEach((tab, index) => {
            if (index === tabIndex) {
                tab.classList.add("active");
            } else {
                tab.classList.remove("active");
            }
        });
    }

    // Назначаем обработчик события клика на каждую вкладку
    tabs.forEach((tab, index) => {
        tab.addEventListener("click", function (event) {
            event.preventDefault();
            showContent(index);
        });
    });

    // Отображаем первую вкладку по умолчанию
    showContent(0);
});
function updateClock() {
    const now = new Date();
    const second = now.getSeconds();
    const minute = now.getMinutes();
    const hour = now.getHours();
    document.getElementById('hour').style.transform = `rotate(${30 * hour + minute / 2}deg)`;
    document.getElementById('minute').style.transform = `rotate(${6 * minute}deg)`;
    document.getElementById('second').style.transform = `rotate(${6 * second}deg)`;
}
setInterval(updateClock, 1000);
updateClock();
        </script>
        
	</head>
	<body>
		<svg class="hidden">
			<defs>
				<path id="tabshape" d="M80,60C34,53.5,64.417,0,0,0v60H80z"/>
			</defs>
		</svg>
		<div class="container">
			
			<section>
				<div class="tabs tabs-style-shape">
					<nav>
						<ul>
							<li>
								<a href="#section-shape-1">
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<span>Main</span>
								</a>
							</li>
							<li>
								<a href="#section-shape-2">
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<span>Periodic Table</span>
								</a>
							</li>
							<li>
								<a href="#section-shape-3">
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<span>Silica & Mid-Ir Fibres</span>
								</a>
							</li>
							<li>
								<a href="#section-shape-4">
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<span>Pump Diodes</span>
								</a>
							</li>
							<li>
								<a href="#section-shape-5">
									<svg viewBox="0 0 80 60" preserveAspectRatio="none"><use xlink:href="#tabshape"></use></svg>
									<span>Calculators</span>
								</a>
							</li>
						</ul>
					</nav>
					<div class="content-wrap">
						<section id="section-shape-1" class="content-current">
              <img src="https://i.postimg.cc/TPjh0VNT/Kurkov.png" class="kurkov-img" align="left">
              <h3 class="kurkov-text"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo, aspernatur dolores magni dicta ab, error labore temporibus impedit sunt possimus sint facilis. Itaque fugiat accusantium repellat doloribus molestiae natus sunt?</h3>
						</section>
						<section id="section-shape-2" class="">
              <div class="container-2">
                <div class="podlojka">
                  <img src="https://i.postimg.cc/15zrqQN7/1.png" alt="" class="podlojka-img">
                </div>
                <div id="clock-container">
                  <div id="clock">
                    <div id="hour" class="hand" style="--color: #ff3d58; --height: 40px; --width: 3px"><i></i></div>
                    <div id="minute" class="hand" style="--color: #00a6ff; --height: 50px; --width: 2px"><i></i></div>
                    <div id="second" class="hand" style="--color: #ffffff; --height: 60px; --width: 1px"><i></i></div>
                    <span style="--i: 1; --j: 0"><i>|</i></span>
                    <span style="--i: 2; --j: 0"><i>|</i></span>
                    <span style="--i: 3; --j: 3"><i>3</i></span>
                    <span style="--i: 4; --j: 0"><i>|</i></span>
                    <span style="--i: 5; --j: 0"><i>|</i></span>
                    <span style="--i: 6; --j: 6"><i>6</i></span>
                    <span style="--i: 7; --j: 0"><i>|</i></span>
                    <span style="--i: 8; --j: 0"><i>|</i></span>
                    <span style="--i: 9; --j: 9"><i>9</i></span>
                    <span style="--i: 10; --j: 0"><i>|</i></span>
                    <span style="--i: 11; --j: 0"><i>|</i></span>
                    <span style="--i: 12; --j: 12"><i>12</i></span>
                  </div>
                </div>
							<div class="periodic" style="padding:0px;";>
                                <div class="periodic-row">
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">1</div>
                                      <div class="symbol">H</div>
                                      <div class="at_details">Hydrogen</div>
                                    </div>
                                  </div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <img src="https://i.postimg.cc/dVkR5j68/png.png" class="mendeleev">
                                  </div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <img src="https://i.postimg.cc/Cx3GXnr9/periodic-table-text-png.png" class="periodic-table-text">
                                  </div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">2</div>
                                      <div class="symbol">He</div>
                                      <div class="at_details">Helium</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row">
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">3</div>
                                      <div class="symbol">Li</div>
                                      <div class="at_details">Lithium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">4</div>
                                      <div class="symbol">Be</div>
                                      <div class="at_details">Beryllium</div>
                                    </div>
                                  </div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">5</div>
                                      <div class="symbol">B</div>
                                      <div class="at_details">Boron</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">6</div>
                                      <div class="symbol">C</div>
                                      <div class="at_details">Carbon</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">7</div>
                                      <div class="symbol">N</div>
                                      <div class="at_details">Nidivogen</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">8</div>
                                      <div class="symbol">O</div>
                                      <div class="at_details">Oxygen</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">9</div>
                                      <div class="symbol">F</div>
                                      <div class="at_details">Fluorine</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">10</div>
                                      <div class="symbol">Ne</div>
                                      <div class="at_details">Neon</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row">
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">11</div>
                                      <div class="symbol">Na</div>
                                      <div class="at_details">Sodium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">12</div>
                                      <div class="symbol">Mg</div>
                                      <div class="at_details">Magnesium</div>
                                    </div>
                                  </div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">13</div>
                                      <div class="symbol">Al</div>
                                      <div class="at_details">Aluminum</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">14</div>
                                      <div class="symbol">Si</div>
                                      <div class="at_details">Silicon</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">15</div>
                                      <div class="symbol">P</div>
                                      <div class="at_details">Phosphorus</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">16</div>
                                      <div class="symbol">S</div>
                                      <div class="at_details">Sulfur</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">17</div>
                                      <div class="symbol">Cl</div>
                                      <div class="at_details">Chlorine</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">18</div>
                                      <div class="symbol">Ar</div>
                                      <div class="at_details">Argon</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row">
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">19</div>
                                      <div class="symbol">K</div>
                                      <div class="at_details">Potassium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">20</div>
                                      <div class="symbol">Ca</div>
                                      <div class="at_details">Calcium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">21</div>
                                      <div class="symbol">Sc</div>
                                      <div class="at_details">Scandium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">22</div>
                                      <div class="symbol">Ti</div>
                                      <div class="at_details">Titanium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">23</div>
                                      <div class="symbol">V</div>
                                      <div class="at_details">Vanadium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">24</div>
                                      <div class="symbol">Cr</div>
                                      <div class="at_details">Chromium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">25</div>
                                      <div class="symbol">Mn</div>
                                      <div class="at_details">Manganese</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">26</div>
                                      <div class="symbol">Fe</div>
                                      <div class="at_details">Iron</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">27</div>
                                      <div class="symbol">Co</div>
                                      <div class="at_details">Cobalt</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">28</div>
                                      <div class="symbol">Ni</div>
                                      <div class="at_details">Nickel</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">29</div>
                                      <div class="symbol">Cu</div>
                                      <div class="at_details">Copper</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">30</div>
                                      <div class="symbol">Zn</div>
                                      <div class="at_details">Zinc</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">31</div>
                                      <div class="symbol">Ga</div>
                                      <div class="at_details">Gallium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">32</div>
                                      <div class="symbol">Ge</div>
                                      <div class="at_details">Germanium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">33</div>
                                      <div class="symbol">As</div>
                                      <div class="at_details">Arsenic</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">34</div>
                                      <div class="symbol">Se</div>
                                      <div class="at_details">Selenium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">35</div>
                                      <div class="symbol">Br</div>
                                      <div class="at_details">Bromine</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">36</div>
                                      <div class="symbol">Kr</div>
                                      <div class="at_details">Krypton</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row">
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">37</div>
                                      <div class="symbol">Rb</div>
                                      <div class="at_details">Rubidium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">38</div>
                                      <div class="symbol">Sr</div>
                                      <div class="at_details">Strontium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">39</div>
                                      <div class="symbol">Y</div>
                                      <div class="at_details">Ytdivium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">40</div>
                                      <div class="symbol">Zr</div>
                                      <div class="at_details">Zirconium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">41</div>
                                      <div class="symbol">Nb</div>
                                      <div class="at_details">Niobium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">42</div>
                                      <div class="symbol">Mo</div>
                                      <div class="at_details">Molybdenum</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">43</div>
                                      <div class="symbol">Tc</div>
                                      <div class="at_details">Technetium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">44</div>
                                      <div class="symbol">Ru</div>
                                      <div class="at_details">Ruthenium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">45</div>
                                      <div class="symbol">Rh</div>
                                      <div class="at_details">Rhodium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">46</div>
                                      <div class="symbol">Pd</div>
                                      <div class="at_details">Palladium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">47</div>
                                      <div class="symbol">Ag</div>
                                      <div class="at_details">Silver</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">48</div>
                                      <div class="symbol">Cd</div>
                                      <div class="at_details">Cadmium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">49</div>
                                      <div class="symbol">In</div>
                                      <div class="at_details">Indium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">50</div>
                                      <div class="symbol">Sn</div>
                                      <div class="at_details">Tin</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">51</div>
                                      <div class="symbol">Sb</div>
                                      <div class="at_details">Antimony</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">52</div>
                                      <div class="symbol">Te</div>
                                      <div class="at_details">Tellurium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">53</div>
                                      <div class="symbol">I</div>
                                      <div class="at_details">Iodine</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">54</div>
                                      <div class="symbol">Xe</div>
                                      <div class="at_details">Xenon</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row">
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">55</div>
                                      <div class="symbol">Cs</div>
                                      <div class="at_details">Cesium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">56</div>
                                      <div class="symbol">Ba</div>
                                      <div class="at_details">Barium</div>
                                    </div>
                                  </div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">72</div>
                                      <div class="symbol">Hf</div>
                                      <div class="at_details">Hafnium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">73</div>
                                      <div class="symbol">Ta</div>
                                      <div class="at_details">Tantalum</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">74</div>
                                      <div class="symbol">W</div>
                                      <div class="at_details">Tungsten</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">75</div>
                                      <div class="symbol">Re</div>
                                      <div class="at_details">Rhenium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">76</div>
                                      <div class="symbol">Os</div>
                                      <div class="at_details">Osmium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">77</div>
                                      <div class="symbol">Ir</div>
                                      <div class="at_details">Iridium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">78</div>
                                      <div class="symbol">Pt</div>
                                      <div class="at_details">Platinum</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">79</div>
                                      <div class="symbol">Au</div>
                                      <div class="at_details">Gold</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">80</div>
                                      <div class="symbol">Hg</div>
                                      <div class="at_details">Mercury</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">81</div>
                                      <div class="symbol">Tl</div>
                                      <div class="at_details">Thallium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">82</div>
                                      <div class="symbol">Pb</div>
                                      <div class="at_details">Lead</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">83</div>
                                      <div class="symbol">Bi</div>
                                      <div class="at_details">Bismuth</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">84</div>
                                      <div class="symbol">Po</div>
                                      <div class="at_details">Polonium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">85</div>
                                      <div class="symbol">At</div>
                                      <div class="at_details">Astatine</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">86</div>
                                      <div class="symbol">Rn</div>
                                      <div class="at_details">Radon</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row">
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">87</div>
                                      <div class="symbol">Fr</div>
                                      <div class="at_details">Francium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">88</div>
                                      <div class="symbol">Ra</div>
                                      <div class="at_details">Radium</div>
                                    </div>
                                  </div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">104</div>
                                      <div class="symbol">Rf</div>
                                      <div class="at_details">Rutherfordium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">105</div>
                                      <div class="symbol">Db</div>
                                      <div class="at_details">Dubnium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">106</div>
                                      <div class="symbol">Sg</div>
                                      <div class="at_details">Seaborgium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">107</div>
                                      <div class="symbol">Bh</div>
                                      <div class="at_details">Bohrium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">108</div>
                                      <div class="symbol">Hs</div>
                                      <div class="at_details">Hassium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">109</div>
                                      <div class="symbol">Mt</div>
                                      <div class="at_details">Meitnerium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">110</div>
                                      <div class="symbol">Ds</div>
                                      <div class="at_details">Darmstadtium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">111</div>
                                      <div class="symbol">Rg</div>
                                      <div class="at_details">Roentgenium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">112</div>
                                      <div class="symbol">Cn</div>
                                      <div class="at_details">Copernicium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">113</div>
                                      <div class="symbol">Nh</div>
                                      <div class="at_details">Nihonium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">114</div>
                                      <div class="symbol">Fl</div>
                                      <div class="at_details">Flerovium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">115</div>
                                      <div class="symbol">Mc</div>
                                      <div class="at_details">Moscovium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">116</div>
                                      <div class="symbol">Lv</div>
                                      <div class="at_details">Livermorium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">117</div>
                                      <div class="symbol">Ts</div>
                                      <div class="at_details">Tennessine</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">118</div>
                                      <div class="symbol">Og</div>
                                      <div class="at_details">Oganesson</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row"></div>
                                <div class="periodic-row">
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">57</div>
                                      <div class="symbol">La</div>
                                      <div class="at_details">Lanthanum</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">58</div>
                                      <div class="symbol">Ce</div>
                                      <div class="at_details">Cerium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">59</div>
                                      <div class="symbol">Pr</div>
                                      <div class="at_details">Praseodymium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">60</div>
                                      <div class="symbol">Nd</div>
                                      <div class="at_details">Neodymium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">61</div>
                                      <div class="symbol">Pm</div>
                                      <div class="at_details">Promethium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">62</div>
                                      <div class="symbol">Sm</div>
                                      <div class="at_details">Samarium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">63</div>
                                      <div class="symbol">Eu</div>
                                      <div class="at_details">Europium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">64</div>
                                      <div class="symbol">Gd</div>
                                      <div class="at_details">Gadolinium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">65</div>
                                      <div class="symbol">Tb</div>
                                      <div class="at_details">Terbium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">66</div>
                                      <div class="symbol">Dy</div>
                                      <div class="at_details">Dysprosium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">67</div>
                                      <div class="symbol">Ho</div>
                                      <div class="at_details">Holmium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">68</div>
                                      <div class="symbol">Er</div>
                                      <div class="at_details">Erbium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">69</div>
                                      <div class="symbol">Tm</div>
                                      <div class="at_details">Thulium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">70</div>
                                      <div class="symbol">Yb</div>
                                      <div class="at_details">Ytterbium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">71</div>
                                      <div class="symbol">Lu</div>
                                      <div class="at_details">Lutetium</div>
                                    </div>
                                  </div>
                                </div>
                                <div class="periodic-row">
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell"></div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">89</div>
                                      <div class="symbol">Ac</div>
                                      <div class="at_details">Actinium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">90</div>
                                      <div class="symbol">Th</div>
                                      <div class="at_details">Thorium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">91</div>
                                      <div class="symbol">Pa</div>
                                      <div class="at_details">Protactinium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">92</div>
                                      <div class="symbol">U</div>
                                      <div class="at_details">Uranium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">93</div>
                                      <div class="symbol">Np</div>
                                      <div class="at_details">Neptunium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">94</div>
                                      <div class="symbol">Pu</div>
                                      <div class="at_details">Plutonium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">95</div>
                                      <div class="symbol">Am</div>
                                      <div class="at_details">Americium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">96</div>
                                      <div class="symbol">Cm</div>
                                      <div class="at_details">Curium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">97</div>
                                      <div class="symbol">Bk</div>
                                      <div class="at_details">Berkelium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">98</div>
                                      <div class="symbol">Cf</div>
                                      <div class="at_details">Californium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">99</div>
                                      <div class="symbol">Es</div>
                                      <div class="at_details">Einsteinium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">100</div>
                                      <div class="symbol">Fm</div>
                                      <div class="at_details">Fermium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">101</div>
                                      <div class="symbol">Md</div>
                                      <div class="at_details">Mendelevium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">102</div>
                                      <div class="symbol">No</div>
                                      <div class="at_details">Nobelium</div>
                                    </div>
                                  </div>
                                  <div class="cell">
                                    <div class="element">
                                      <div class="at_num">103</div>
                                      <div class="symbol">Lr</div>
                                      <div class="at_details">Lawrencium</div>
                                    </div>
                                  </div>
                                </div>
                                <div style="clear: both;"></div>
                              </div>
						</section>
						<section id="section-shape-3" class="">
              <div class="season_tabs">
                <div class="season_tab">
                    <input type="radio" id="tab-1" name="tab-group-1" checked>
                    <label for="tab-1">Nd-doped</label>
                    <div class="season_content">
                      <img src="https://i.postimg.cc/V65D1r9y/silica-Nd-1.jpg" class="silica-Nd-1" align="left">
                      <img src="https://i.postimg.cc/LXqBGdR2/silica-Nd-2.jpg" class="silica-Nd-2" align="right">
                      <h3 class="silica-Nd-text"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam laboriosam odio provident ipsa hic totam enim quisquam cum nulla ducimus aperiam</h3>
                    </div> 
                </div>
                 
                <div class="season_tab">
                    <input type="radio" id="tab-2" name="tab-group-1">
                    <label for="tab-2">Yb-doped</label>
                    
                    <div class="season_content">
                      <img src="https://i.postimg.cc/k5t10t72/silica-Yb-1.jpg" class="silica-Yb-1" align="left">
                      <h3 class="silica-Yb-text"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe fuga ipsa consequuntur obcaecati voluptates, dicta consectetur repudiandae nesciunt sint recusandae. Cumque iste exercitationem error?</h3>
                    </div> 
                </div>
                 
                 <div class="season_tab">
                    <input type="radio" id="tab-3" name="tab-group-1">
                    <label for="tab-3">Tm-doped</label>
                  
                    <div class="season_content">
                      <img src="https://i.postimg.cc/13VbQdHR/silica-Tm-1.jpg" class="silica-Tm-1" align="left">
                      <h3 class="silica-Tm-text"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Similique aut ut magni ipsum necessitatibus culpa iusto itaque delectus id et. Consequuntur ducimus dignissimos ipsa quasi fugiat id mollitia, eaque repudiandae.</h3>
                    </div>                  
                </div>
                <div class="season_tab">
                    <input type="radio" id="tab-4" name="tab-group-1" checked>
                    <label for="tab-4">Tb-doped</label>
                    
                    <div class="season_content">
                      <img src="https://i.postimg.cc/761fQXcm/mid-ir-Tb-1.jpg" class="mid-ir-Tb-1" align="left">
                      <h3 class="mid-ir-Tb-text"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam laboriosam odio provident ipsa hic totam enim quisquam cum nulla ducimus aperiam veniam sint vitae consectetur, voluptate illum quasi dolorum maxime!</h3>
                    </div> 
                </div>
                <div class="season_tab">
                    <input type="radio" id="tab-5" name="tab-group-1">
                    <label for="tab-5">Dy-doped</label>
                    
                    <div class="season_content">
                      <img src="https://i.postimg.cc/d0wMjB2q/mid-ir-Dy-1.jpg" class="mid-ir-Dy-1" align="left">
                      <h3 class="mid-ir-Dy-text"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe fuga ipsa consequuntur obcaecati voluptates, dicta consectetur repudiandae nesciunt sint recusandae. Cumque iste exercitationem error?</h3>
                    </div> 
                </div>
                <div class="season_tab">
                    <input type="radio" id="tab-6" name="tab-group-1">
                    <label for="tab-6">Ce-doped</label>
                  
                    <div class="season_content">
                      <img src="https://i.postimg.cc/VkvyGR51/silica-Ce-1.jpg" class="mid-ir-Ce-1" align="left">
                      <img src="https://i.postimg.cc/4dTSgb4Y/silica-Ce-2.jpg" class="mid-ir-Ce-2" align="left">
                      <h3 class="mid-ir-Ce-text"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Similique aut ut magni ipsum necessitatibus culpa iusto itaque delectus id et. Consequuntur ducimus dignissimos ipsa quasi fugiat id mollitia, eaque repudiandae.</h3>
                    </div>                  
             </div>
                
						</section>
						<section id="section-shape-4" class="">

						</section>
						<section id="section-shape-5" class="">

						</section>
					</div><!-- /content -->
				</div><!-- /tabs -->
			</section>

		</div><!-- /container -->
		<script src="js/cbpFWTabs.js">

;( function( window ) {
	
	'use strict';

	function extend( a, b ) {
		for( var key in b ) { 
			if( b.hasOwnProperty( key ) ) {
				a[key] = b[key];
			}
		}
		return a;
	}

	function CBPFWTabs( el, options ) {
		this.el = el;
		this.options = extend( {}, this.options );
  		extend( this.options, options );
  		this._init();
	}

	CBPFWTabs.prototype.options = {
		start : 0
	};

	CBPFWTabs.prototype._init = function() {
		// tabs elems
		this.tabs = [].slice.call( this.el.querySelectorAll( 'nav > ul > li' ) );
		// content items
		this.items = [].slice.call( this.el.querySelectorAll( '.content-wrap > section' ) );
		// current index
		this.current = -1;
		// show current content item
		this._show();
		// init events
		this._initEvents();
	};

	CBPFWTabs.prototype._initEvents = function() {
		var self = this;
		this.tabs.forEach( function( tab, idx ) {
			tab.addEventListener( 'click', function( ev ) {
				ev.preventDefault();
				self._show( idx );
			} );
		} );
	};

	CBPFWTabs.prototype._show = function( idx ) {
		if( this.current >= 0 ) {
			this.tabs[ this.current ].className = this.items[ this.current ].className = '';
		}
		// change current
		this.current = idx != undefined ? idx : this.options.start >= 0 && this.options.start < this.items.length ? this.options.start : 0;
		this.tabs[ this.current ].className = 'tab-current';
		this.items[ this.current ].className = 'content-current';
	};

	// add to global namespace
	window.CBPFWTabs = CBPFWTabs;

})( window );

		</script>
		<script>
			(function() {

				[].slice.call( document.querySelectorAll( '.tabs' ) ).forEach( function( el ) {
					new CBPFWTabs( el );
				});

			})();
		</script>
	</body>
</html>
