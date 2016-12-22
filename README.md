# font-awesome-lists
In this tutorial, [Solodev](https://www.solodev.com/) will show some common implementations for you to build lists using [Font Awesome] (http://fontawesome.io/) Icons and [Bootstrap](http://getbootstrap.com/) in your next [web design](https://www.solodev.com/blog/) project. Lists are prominent and diverse. One website may need to list their products using visuals while another lists their feature set using checkmarks.

Some applications use checkboxes so the user can mark off what they have completed and what is left to be done. Font Awesome can accommodate any kind of list that needs to be built for your website. In this tutorial, Solodev will show some common implementations of using Font Awesome and Bootstrap to build lists.

## Tutorial

For detailed instructions, visit Solodev's [Building Lists with Font Awesome and Bootstrap](https://www.solodev.com/blog/web-design/building-lists-with-font-awesome-and-bootstrap.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/2L4tuvpm/).

## HTML

The various list examples contain the following basic HTML markup.

device-type.html
```
<div class="list-group">
   <a href="#" class="list-group-item active">
   Device Type
   </a>
   <a href="#" class="list-group-item"><i class="fa fa-check" aria-hidden="true"></i>
   Desktop</a>
   <a href="#" class="list-group-item"><i class="fa fa-check" aria-hidden="true"></i>
   Mobile</a>
   <a href="#" class="list-group-item"><i class="fa fa-check" aria-hidden="true"></i>
   Tablet</a>
</div>
```
operating-system.html
```
<div class="list-group">
   <a href="#" class="list-group-item active">
   Operating System
   </a>
   <a href="#" class="list-group-item"><i class="fa fa-check-circle" aria-hidden="true"></i>
   Windows</a>
   <a href="#" class="list-group-item"><i class="fa fa-check-circle" aria-hidden="true"></i>
   OS X</a>
   <a href="#" class="list-group-item"><i class="fa fa-check-circle" aria-hidden="true"></i>
   Linux</a>
</div>
```
to-do.html
```
<div class="list-group">
   <a href="#" class="list-group-item active">
   To-Do List
   </a>
   <a href="#" class="list-group-item"><i class="fa fa-check-square-o" aria-hidden="true"></i>
   Go Christmas Shopping</a>
   <a href="#" class="list-group-item"><i class="fa fa-check-square-o" aria-hidden="true"></i>
   Pick up movie tickets from theatre</a>
   <a href="#" class="list-group-item"><i class="fa fa-square-o" aria-hidden="true"></i>
   Write Christmas Cards</a>
   <a href="#" class="list-group-item"><i class="fa fa-check-square-o" aria-hidden="true"></i>
   Pick up Jon from Airport</a>
</div>
```
features.html
```
<div class="list-group">
   <a href="#" class="list-group-item active">
   Features
   </a>
   <a href="#" class="list-group-item"><i class="fa fa-check-square" aria-hidden="true"></i>
   CRM - Sales Cloud</a>
   <a href="#" class="list-group-item"><i class="fa fa-check-square" aria-hidden="true"></i>
   E-Commerce</a>
     <a href="#" class="list-group-item"><i class="fa fa-check-square" aria-hidden="true"></i>
   CMS - Website Builder</a>
</div>
```

## CSS

All necessary CSS is in lists.css

## External Includes

This tutorial contains the following third party resources.
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300" rel="stylesheet">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="lists.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
