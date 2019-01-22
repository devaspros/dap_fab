# DAP FAB

DAP FAB is a jQuery plugin to create Material Design Floating Action Button(for the web). Forked and modified from [KC FAB](https://github.com/katrincwl/kc_fab/)

## Examples

- [KC FAB jsfiddle demo](https://jsfiddle.net/katrinluk/8wxho9cw/3/)
- [jqueryscript.net example](http://www.jqueryscript.net/menu/Material-Design-Floating-Action-Button-with-jQuery-KC-FAB.html) of [KC FAB usage](http://www.jqueryscript.net/demo/Material-Design-Floating-Action-Button-with-jQuery-KC-FAB/)

## How to use

First of all, you need to have a DOM element to hold action buttons, e.g:

```html
<div class="kc_fab_wrapper" ></div>
```

Then in your script, calling the kc_fab on your DOM element. You can pass in an object array as option to tell the plugin the buttons style and the anchors' link.

```js
var links = [
  {   /* The first object will be the main button */
      "bgcolor":"red",
      "icon":"+"
  },
  /* Following are the hidden button list */
  {
      "url":"http://www.example.com",
      "bgcolor":"red",
      "color":"#fffff",
      "icon":"<i class='fa fa-phone'></i>",
      "target":"_blank"
  },
  {
      "url":"http://www.example.com",
      "bgcolor":"black",
      "color":"white",
      "icon":"<i class='fa fa-music'></i>",
      "id":"id_item"
  }
]

$('.kc_fab_wrapper').kc_fab(links);
```

## License

Copyright (c) 2019 Dev As Pros Licensed under the [MIT license].

[MIT license]: https://github.com/devaspros/dap_fab/blob/master/LICENSE
