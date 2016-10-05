# scrollspy
In this article, Solodev shows you how to add further ease of navigation to your website using scrollspy, a tool that automatically updates links in your website navigation based on the scroll position of your website.

## Tutorial

For detailed instructions, view Solodev's [Adding Scrollspy to your Website](https://www.solodev.com/blog/web-design/adding-scrollspy-to-your-website.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/jd6s1fq9/).

## HTML

The scrollspy has the following basic HTML markup.

```
<nav class="navbar navbar-inverse navbar-fixed-top">
  <div class="container-fluid">
    <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
      </button>
       <a class="navbar-brand" href="#"> <img src="https://www.solodev.com/assets/email/logo.png" alt="Logo Solodev"></a>
    </div>
    <div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav">
          <li><a href="#section1">Section 1</a></li>
          <li><a href="#section2">Section 2</a></li>
          <li><a href="#section3">Section 3</a></li>
          <li><a href="#section4">Section 4</a></li>
        </ul>
      </div>
    </div>
  </div>
</nav>

<div id="section1" class="container-fluid">
  <h1>Section 1</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! <strong>Clearly another Festivus Miracle!</strong></p>   
</div>
<div id="section2" class="container-fluid">
  <h1>Section 2</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>   
</div>
<div id="section3" class="container-fluid">
  <h1>Section 3</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
</div>
<div id="section4" class="container-fluid">
  <h1>Section 4</h1>
  <p>Try to scroll this section and look at the navigation bar while scrolling! Try to scroll this section and look at the navigation bar while scrolling!</p>
</div>
```

## CSS

All necessary CSS is included in scrollspy.css.

## External Includes

This tutorial includes the following third party resources.
```
<script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/holder/2.9.4/holder.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">

```
