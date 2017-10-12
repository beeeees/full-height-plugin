## Full height jQuery plugin 

Demo: [Codepen](https://codepen.io/beeeees/pen/WZKWrM)

Use jQuery to make an element full height of the browser window, even on resize. A bit outdated now, but useful for certain cross-browser support requirements.  Hopefully you can use [CSS viewports](https://css-tricks.com/fun-viewport-units/) now: `height: 100vh`.

Requires [JQuery](https://code.jquery.com/)

To initialize, call on the element of your choice:

 ```
  $(document).ready(function() {
    $('.full-height').fullHeight();
  });
```