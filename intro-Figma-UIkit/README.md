# Основни елементи от дизайн системата на "Подкрепи.бг"!
#### *Тук са поместени базовите положения от дизайн системата, които следва да се използват. Разработен е за [Material UI Theme Creator](https://bareynol.github.io/mui-theme-creator/). В обясненията са дадени връзки към оригиналните файлове във Фигма, в случай че ще се ползва друг инструмент.*
<br>
<br>

## Съдържание:

> 01. ### [Основна информация](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/README.md#1-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%B0-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F)<br>
> 02. ### [Цветове](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/README.md#%D1%86%D0%B2%D0%B5%D1%82%D0%BE%D0%B2%D0%B5-1)<br>
> 03. ### [Шрифтове](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/README.md#%D1%88%D1%80%D0%B8%D1%84%D1%82%D0%BE%D0%B2%D0%B5-1)<br>
> 04. ###  [Допълнителна информация за Фигма](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/README.md#%D0%B4%D0%BE%D0%BF%D1%8A%D0%BB%D0%BD%D0%B8%D1%82%D0%B5%D0%BB%D0%BD%D0%B0-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F-%D0%B7%D0%B0-%D1%84%D0%B8%D0%B3%D0%BC%D0%B0-1)<br>
> 05. ### [Приложения](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/README.md#%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-1)
>   * [01. Приложение][2] Кратки пътища във Фигма
>   * [02. Приложение][3] Видеа<br>
>   * [03. Приложение][4] Статии<br>

<br>

## 1. Основна информация

#### *Този файл е създаден с цел улеснение написването на код, използващ характерните за "Подкрепи.бр" бранд елементи. Той не е изчерпателен и ще бъде допълван!*
<br>

Всички визии, за които ще се пише код, ще се съхраняват [тук](https://www.figma.com/file/MmvFKzUv6yE5U2wrOpWtwS/Podkrepi.bg?node-id=8281%3A24205). При селектиране на фрейма или на отделен негов елемент можете да получите допълнителна информация под формата на код. За целта трябва да отидете на меню Inspect:<br>

![](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/intro-Figma-UIkit-img/Inspect.png) 

<br>

В [02. Приложение][3] ще откриете няколко кратки видеа, които ще ви дадат допълнителна информация, която може да ви бъде полезна във Фигма.
<br>

[03. Приложение][4] съдържа основните насоки за работа, адаптирани за разработчици.

<br>

##### обратно в [съдържанието][1]

<br>

## Цветове

След въвеждане на основния цвят [Material UI Theme Creator](https://bareynol.github.io/mui-theme-creator/) автоматично попълва  останалите съгласно дизайн системата на Подкрепи.бг. В таблицата по-долу са дадено основните цветове, които трябва да се заложат. В празните полета ще бъдат дописвани цветове, които ще се различават от тези, което се генерират автоматично и трябва да бъдат  променени допълнително чрез дописване в кода. <br>
Ако ще ползвате различен инструмент за писане на код - всички цветове на Подкрепи.бг дизайн системата можете да намерите [тук](https://www.figma.com/file/MmvFKzUv6yE5U2wrOpWtwS/Podkrepi.bg?node-id=38%3A4557).
| 	Theme colors	                        | 	Primary | 	Secondary| Error	 | 	Info	 | 	Warning	 | Success	| 
| 	:-----	                                | 	:-----	| 	:-----	 | :-----	 | 	:-----	 | 	:-----	 | :-----	| 	
| 	main	                                | 	![#4AC3FF](https://via.placeholder.com/15/4AC3FF/000000?text=+) `#4AC3FF`	| 	![#F6992B](https://via.placeholder.com/15/F6992B/000000?text=+) `#F6992B`	 | ![#FF7DB8](https://via.placeholder.com/15/FF7DB8/000000?text=+) `#FF7DB8`	| 	![#D2F9FF](https://via.placeholder.com/15/D2F9FF/000000?text=+) `#D2F9FF`	| 	![#FFA45A](https://via.placeholder.com/15/FFA45A/000000?text=+) `#FFA45A`	 | ![#284E84](https://via.placeholder.com/15/284E84/000000?text=+) `#284E84`	| 
| 	light	                                | 		| 		 | 	| 		| 		 | 	| 	 
| 	dark	                                | 		| 		 | 	| 		| 		 | 	| 	
| 	contrast	                            | 		| 		 | 	| 		| 		 | 	| 		
| 	.../state/contained-hover-background	| 		| 		 | 	| 		| 		 | 	| 	 	
| 	.../state/outlined-hover-background	    | 		| 		 | 	| 		| 		 | 	| 	 	
| 	.../state/outlined-resting-border	    | 		| 		 | 	| 		| 		 | 	| 	 	

<br>

##### обратно в [съдържанието][1]
<br>

## Шрифтове 

Основните шрифтове, които се използват в дизайн системата на Подкрепи.бг, са Montserrat и  Lato. Всички разновидности на шрифтовете може да откриете [тук](https://www.figma.com/file/MmvFKzUv6yE5U2wrOpWtwS/Podkrepi.bg?node-id=38%3A4556). <br>
"Hero text" е отделна категория, която трябва да допишете в кода, когато въвеждате параметрите на шрифтовете. Този вид текст се ползва само на едно място- home page, за надписa върху hero image.
<br>

| 	Style name	    | 	Font name	| 	Font weight	 | Font size	 | 
| 	:-----	        | 	:-----	    | 	:-----	     | :-----	 |
| 	Hero text	    | 	Montserrat	| 	Medium	     | 64 px	 | 
| 	h1	            | 	Montserrat	| 	Bold	     | 50 px	 | 
| 	h2	            | 	Montserrat	| 	Bold	     | 40 px	 | 
| 	h3	            | 	Montserrat	| 	SemiBold	 | 30 px	 | 
| 	body1	        | 	Lato	    | 	Regular	     | 16 px	 | 
| 	body2	        | 	Lato	    | 	Regular	     | 12 px	 | 
| 	button Large	| 	Lato	    | 	SemiBold	 | 18 px	 | 
| 	button Medium	| 	Lato	    | 	Medium	     | 16 px	 | 
| 	button small	| 	Lato	    | 	SemiBold	 | 12 px	 | 

##### *Заб. Това са най-често употребяваните шрифтове, таблицата ще се допълва!*
<br>
<br>

Засега се ползва черен цвят за текстовете, различните проценти отразяват неговата наситеност:
<br>

| 	Text colors	 | Sample	 | 	Description	 | 
| 	:-----	 | 	:-----	 | 	:-----	 | 
| 	text/primary	| 	![#000000](https://via.placeholder.com/15/000000/000000?text=+) `#000000`	100%| 	Text primary	 | 
| 	text/secondary	| 	![#000000](https://via.placeholder.com/15/000000/000000?text=+) `#000000` 60%	| 	Text secondary	 | 
| 	text/disabled	| 	![#000000](https://via.placeholder.com/15/000000/000000?text=+) `#000000` 38%	| 	Text disabled	 |

<br>

##### обратно в [съдържанието][1]
<br>

## Допълнителна информация за Фигма

#### *Ако използвате Mac, то вместо Ctrl следва да използвате Cmd бутона*
<br>

 Основните бутони, които програмистите използват във Фигма, са Ctrl, Alt и i.
> 01. Задържан Ctrl + клик селектира конкретен обект:
> <br> 
> 
> ![](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/intro-Figma-UIkit-img/Ctrl.png)
> <br>
> <br>
> 
> 02. Задържан Alt + hover около обекта показва отстоянията около него:
> <br>
> 
> ![](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/intro-Figma-UIkit-img/Alt.png)
> <br>
> <br>
> 
> 03. Натиснат i + клик селектира конкретен цвят. Това е най-лесният вариант да извадите цвят от компонент. Хекс-кодът в кръгчето трябва да се препише, понеже не може да се копира:
> <br>
> 
> ![](https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/intro-Figma-UIkit-img/i.png)
> <br>
> <br>
>
 За улеснение на работата често се ползват и следните допълнителни клавишни комбинации:
> 01. Ctrl + z <br>
> Redo. Връща назад с една стъпка. Полезно, ако случайно нещо се размести, възстановява предишното положение на файла.
> 01. Ctrl + Наклонена наляво черта<br>
> Скрива/показава UI интерфейса. Важно: ползва се наклонената наляво черта, която се намира до Enter. 
> 01. Ctrl + Alt + Наклонена наляво черта<br>
> Скрива/показава левия UI интерфейс. Важно: ползва се наклонената наляво черта, която се намира до Enter.
> 01. Ctrl + Shift  + ?<br>
> Скрива/показава всички кратки пътища във Фигма.
><br>
><br>
>
>&#x1F4D9; [01. Приложение][2] Всички кратки пътища във Фигма<br>

<br>

##### обратно в [съдържанието][1]

<br>

## Приложения 

>   * [01. Приложение][2] Всички кратки пътища във Фигма
>   * [02. Приложение][3] Серия от кратки ръководства за Фигма, създадени за разработчици.
>   * [03. Приложение][4] Статии<br>

<br>

##### обратно в [съдържанието][1]

<br>

[1]:https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/README.md#%D1%81%D1%8A%D0%B4%D1%8A%D1%80%D0%B6%D0%B0%D0%BD%D0%B8%D0%B5
[2]:https://github.com/podkrepi-bg/design/blob/main/intro-Figma-UIkit/intro-Figma-UIkit-img/01Figma-small.png
[3]:https://www.youtube.com/watch?v=XA4fM5I4GvQ&list=PL7e8VJ_ZN6epq-oiYOufiuPI-fpDC2Mby&index=1
[4]:https://www.figma.com/best-practices/tips-on-developer-handoff/an-overview-of-figma-for-developers/
