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

### The DIV element

The `div` element is normally used as a container for other elements. It can be used to structure and style a part of a layout.

``` html
<div>
  <!--Other HTML Elements-->
</div>
```
### Semantic elements

`<form>`, `<header>`,`<section>` are semantic tags. A semantic element clearly describes its meaning to both the browser and the developer.

`<div>`, `<span>` are not. They tell the browser and the developer nothing about its content.

