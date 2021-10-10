# Pop-ups js and nojs versions

## Description

Pop-ups with nice animation using perspective css property with and without using javascript

## Examples 👁️

![screenshot](https://user-images.githubusercontent.com/91592743/136660457-dbab0ad2-9d14-4377-b0be-78f4537e5883.png)

https://user-images.githubusercontent.com/91592743/136660441-7025ec72-4bde-46db-a760-3a79a74f971f.mp4

---

## Technologies used 🛠️

<h3 align="left"> &nbsp  &nbsp  &nbsp Programming languages</h3>

<a href="https://www.w3.org/html/" target="_blank"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" height="30"/> </a>
<a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" height="30"/> </a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" height="30"/> </a>

<h3 align="left"> &nbsp  &nbsp  &nbsp Helper apps</h3>
<a href="psdetch.com" target="_blank"> <img src="https://html-plus.in.ua/wp-content/uploads/2019/08/studio-psdetch.png" alt="psdetch.com" height="30"/> </a>

---

## Features 💡

⚡️ Nice perspective animation\
⚡️ Easy to use\
⚡️ javascript and noscript versions\
⚡️ noscript version close pop-up by clicking on close btn or space around popup\
⚡️ javascript also close pop-up on hitting Esc key

## How To Use 🔧

Integrate link to open popup by using:

```html
<a href="#popup" class="header__phone popup-link">Pop-up №1</a>
```

For javascript popup add to body this template:

```html
<div id="popup" class="popup">
	<div class="popup__body">
		<div class="popup__content">
			<a href="#header" class="popup__close close-popup">X</a>
			<div class="popup__title">Pop-up window 1</div>
			<div class="popup__text">
				Lorem ipsum dolor sit amet consectetur adipisicing elit!
			</div>
		</div>
	</div>
</div>
```

For noscript version add `<a href="#header" class="popup__area"></a>` link for pup-up closing by clicking out of popup area:

```html
<div id="popup" class="popup">
	<a href="#header" class="popup__area"></a>
	<div class="popup__body">
		<div class="popup__content">
			<a href="#header" class="popup__close close-popup">X</a>
			<div class="popup__title">Pop-up window 1</div>
			<div class="popup__text">
				Lorem ipsum dolor sit amet consectetur adipisicing elit!
			</div>
		</div>
	</div>
</div>
```

---

## Acknowledgments 🎁

Thanks to
[Евгений Андриканич](https://fls.guru/) ,
[Vladilen Minin](https://www.youtube.com/c/VladilenMinin) ,
[CS50](https://cs50.harvard.edu/college/2021/fall/) ,
[Александр Лущенко](https://itgid.info/) ,
[Vadim Makeev](https://www.youtube.com/channel/UCaTfYudJUVA8cV_But8KZVQ) ,
[Safak](https://github.com/safak) ,
[Adrian Hajdin](https://www.completepathtojavascriptmastery.com/) ,
[Sumit Dey](https://www.youtube.com/c/BackbenchCoder)
for motivational and helpful content

---
