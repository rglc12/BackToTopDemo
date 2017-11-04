# Back to Top Demo
A demonstration of a simple Back to Top button using Bootstrap and JavaScript/jQuery.

## HTML

The following code is what displays the Back to Top Icon on the webpage (Lines 94 - 96):

```html
  <div id="back-to-top">
    <a href="#jumbotron"><i class="fa fa-chevron-circle-up fa-3x"></i></a>
  </div>
```

## SmoothScroll

The Smooth Scroll jQuery code is a custom script with smooth scroll animation with customizable variable and variations of scroll speed.

You can edit the speed of the Smooth Scroll by changing the 700 int in the function (line 12):

```javascript
$('html, body').animate({
       scrollTop: $(this.hash).offset().top -50
     }, 700, function()
```

Larger the number, the slower the scroll.
Look at js/smoothscroll.js for more information.
