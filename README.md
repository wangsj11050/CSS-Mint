CSS-Mint
========

CSS Mint is an Open Source UI Kit built to cut down front end development time and ease up Layout and Structuring of your Web Application. Built on top of Normalize.css, It handles cross browser inconsistencies and aims at reducing markup. 

It follows the OOCSS approach for better and cleaner CSS styling.

CSS Mint recommends HTML5 based semantic style for writing markup. All examples and the bundled test project is based on the same approach.

## Components

#### Header

To create a header element, simply add a ``header`` class to the header tag along with any of the optional styling classes.

Example - 

```html
	<header class="header"></header>
```
![CSS Mint Header](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/header/header.png)

Adding a right navbar in the header element  

```html
	<div class="nav-right">
		<nav class="navbar">
	 		<ul>
	        	<li><a class="ease-in-out active" href="">Home</a></li>
	        	<li><a class="ease-in-out" href="">About</a></li>
	            <li><a class="ease-in-out" href="">Contact</a></li>
	        </ul>
	    </nav>
	</div>
```

![CSS Mint Header Navbar](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/header/header%20nav-right.png)


##### Optional Classes

```html
	<header class="header default"></header>
```
![CSS Mint Header Default](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/header/header%20default.png)

```html
	<header class="header light"></header>
```
![CSS Mint Header Light](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/header/header%20light.png)

```html
	<header class="header dark"></header>
```
![CSS Mint Header Dark](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/header/header%20dark.png)

<br/>
#### Navbar

Simply add a ``navbar`` class to the nav tag and add an unordered list with refrences to your nav links. The same can be used with the header component as shown above.

Example - 

```html
	<nav class="navbar">
 		<ul>
        	<li><a class="ease-in-out active" href="">Home</a></li>
        	<li><a class="ease-in-out" href="">About</a></li>
            <li><a class="ease-in-out" href="">Contact</a></li>
        </ul>
    </nav>
```

<br/>
#### Panel

Create a panel to contain information.

Example - 

```html
	<div class="panel">
		Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore.
	</div>
```

<br/>
#### The Grid

CSS Mint comes bundled with a 6-column grid system that can be used to create complex layouts. Add columns that can be spanned from 16% ``(col-span-1)`` to 100% ``(col-span-6)`` of the screen width. These columns need to be wrapped within a grid row ``(gr-row)`` container. 

Example - 

```html
	<div class="gr-row">
		<div class="col-span-3">
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore.
		</div>
		<div class="col-span-3">
			Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore.
		</div>
	</div>
```

![CSS Mint Grid System](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/grid/grid.png)

<br/>
#### Typography

CSS Mint has built in classes to customise text.

Example - 

```html
	<!-- For lighter text -->
	<p class="font-light"></p> 
	<!-- For normal text -->
	<p class="font-normal"></p>
	<!-- For bolder text -->
	<p class="font-bold"></p> 

	<!-- Align text to left -->
	<p class="align-left"></p>
	<!-- Align text to right -->
	<p class="align-right"></p>
	<!-- Align text to center -->
	<p class="align-center"></p>
	<!-- Justify text -->
	<p class="align-justify"></p>

	<!-- For smaller text size -->
	<p class="text-small"></p> 
	<!-- For normal text size -->
	<p class="text-normal"></p> 
	<!-- For bigger text size -->
	<p class="text-big"></p> 
```

<br/>
#### Buttons

Add a ``btn`` class to a button element and add any of the optional styling classes.

Example - 

```html
	<button class="btn"></button>
```

##### Optional Classes

```html
	<button class="btn default"></button>
	<button class="btn primary"></button>
	<button class="btn success"></button>
	<button class="btn info"></button>
	<button class="btn warning"></button>
	<button class="btn error"></button>
```

![CSS Mint buttons](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/button/buttons.png)

Make simple line buttons by adding a class ``line`` to the button element along with the ``btn`` class

![CSS Mint line buttons](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/button/buttons-line.png)

Make buttons rounded by adding a class ``rounded`` to the button element along with the ``btn`` class

![CSS Mint rounded buttons](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/button/buttons-rounded.png)

You can also make small or large sized buttons by adding a class ``small`` or ``large`` to the button element along with the ``btn`` class

![CSS Mint size buttons](https://raw.githubusercontent.com/ArunMichaelDsouza/CSS-Mint/master/test/screenshots/button/buttons-size.png)
























