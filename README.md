# FRONTEND DEVELOPMENT

## HTML

### The \<head\> tag

The `<head>` element provides metada (information) about the HTML document

``` html
<html>
  <head>
    <title>My web page title</title>
    <link rel="stylesheet" href="style.css">
  </head>
<\html>
```

### The \<body\> tag

The `<body>` element defines the main content of the web page. It is the viewable portion of a web page.

``` html
<html>
  <head>
  </head>
    
  <body>
    <p>This is a closing tag.</p>
    <!--These are singletons, they do not have closing tags-->
    <br> 
    <img>
    <link>
  </body>
<\html>
```

### HTML Attributes

HTML attributes have the format property:value. In the example below we have the `src` and `alt` attributes of the `img` element.

``` html
<img src="myimage.jpg" alt="a picture of me">
```

####  Class and ID attributes

The `class` attribute is most commonly used to point to a style in CSS. The CSS will use the `class` as a selector. More on that later!

The `id` attribute is most commonly used in JavaScript


``` html
<p class="slogan" id="slogan"></p>
```

### The div element

The `div` element is normally used as a container for other elements. It can be used to structure and style a part of a layout.

``` html
<div>
  <!--Other HTML Elements-->
</div>
```
### Semantic elements

`<form>`, `<header>`,`<section>` are semantic tags. A semantic element clearly describes its meaning to both the browser and the developer.

`<div>`, `<span>` are not. They tell the browser and the developer nothing about its content.

## CSS

An acronym for Cascading Style Sheets. CSS is a language for providing style to HTML elements. CSS can be defined inside of a HTML document with the `<style>` tag, or in a separate CSS file.

### CSS Terminology

In the example below we have two rulesets. 

``` css
body {
  background-color: gray;
  font-size: 30px;
} 

p {
  color:green;
}
```

* Each ruleset starts with a selector. 
* The selector can be a HTML element, a class or an id. 
* Inside the curly braces you have the declarations of the ruleset. 
* Each declaration consists of a CSS property name and the CSS value.
  
 
### CSS Units

* CSS provides absolute and relative units to define a length
* It's expressed by a number value + the unit: i.e. `fontsize: 30px;`

#### CSS Absolute Units

* Absolute units are fixed units and therefore will not change between different screen sizes (unless media queries are used)
* cm, mm, in, px, pt, pc (picas)

#### CSS Relative Units

* Relative units are relative to another property, thus will change between different screen sizes automatically.
* %, em, rem, ww, vh, vmin, vmax (viewport height, viewport min & max)
  
### CSS Multiple Selectors

Use multiple selectors to apply the same ruleset to multiple HTML elements:

``` css
body, p {
  background-color: gray;
  font-size: 30px;
}
```

### CSS Functions

This example shows the usage of two CSS functions (`rgba` and `calc`):

``` css
body {
  background-color: rgba(0,0,0,0.4);
  margin: calc(2em * 5em);
}
```

### CSS Animations

* CSS allows you to animate HTML elements through both the `animation` property and the `transition` property.
* The `animation` property, along with `keyframes` allows you to create more complex animations.
* The `transition` property allows you to transition between two different CSS values.

### CSS Media Queries

* Media queries allow you to define different rulesets for different screen sizes (Responsive CSS/Responsive Design/Responsive Web Design RWDS)
* It allows a page to adapt accordingly to varying screen sizes.
  
``` css
@media only screen and (min-width:650px) {
  rulesets here
}
```

## JavaScript

* JavaScript is a scripting language for implementing features like UI interactivity, animations, 2D/3D graphics, image carousels, etc...
* It can be written in the HTML document with the script tag, or inside an external javascript file (.js)
* Modern frontend development framework/libraries like React, Vue and Angular are written with JavaScript.



