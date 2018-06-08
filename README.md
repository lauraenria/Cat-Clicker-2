# New Project Requirements for Cat Clicker
**Visuals**

* The application should display two cats. Each cat includes
  * the cat's name
  * a picture of the cat
  * text showing the number of clicks

* The specifics of the layout do not matter, so style it however you'd like.

**Interaction**

* The number of clicks should increment when each cat picture is clicked.

**Inspiration**

![Cute Cat for Inspiration](https://lh3.ggpht.com/kixazxoJ2ufl3ACj2I85Xsy-Rfog97BM75ZiLaX02KgeYramAEqlEHqPC3rKqdQj4C1VFnXXryadFs1J9A=s0#w=640&h=496)

Thanks to [chewie](https://www.flickr.com/photos/chewie/2290467335) for the photo.

**Resources**

In case you need a refresher on events and event listeners, here are some links.

If you're writing Cat Clicker with vanilla JS (no jQuery), you'll be adding the "click" event with [elem.addEventListener()](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget.addEventListener).

```javascript
var elem = document.getElementById('my-elem');
elem.addEventListener('click', function(){
  //the element has been clicked... do stuff here
}, false);
If you're using jQuery, you'll be adding the "click" event listener with [jQuery.click()](http://api.jquery.com/click/).

```

```javascript

$('#my-elem').click(function(e) {
  //the element has been clicked... do stuff here
});

```

ps. Use ES6
