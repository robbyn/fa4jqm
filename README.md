fa4jqm
======

This is my attempt at integrating FontAwesome with JQuery mobile 1.4.

To use it in your project, copy fa-icons.css in your css directory, the fontawesome font files in your css/fonts
directory, Add reference to fa-icons.css either in your html files:

```html
<link rel="stylesheet" href="css/fatest.css" />
```

or in another css file:

```css
@import "fa-icons.css";
```

To use an awesome icon instead of a standard jquery mobile icon on an element, instead of attributing the class <i>ui-icon-&lt;icon-name&gt;</i> to the element, add both <i>fa</i> and <i>fa-&lt;icon-name&gt;</i> classes to the
element.

For instance, instead of using:

```html
<a href="#page2" class="ui-btn ui-btn-icon-left ui-icon-carat-r">Next</a>
```

use:

```html
<a href="#page2" class="ui-btn ui-btn-icon-left fa fa-chevron-right">Next</a>
```
