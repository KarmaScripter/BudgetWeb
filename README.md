﻿## A quick and dirty HTML, CSS, and JS website template

## ![](https://github.com/KarmaScripter/BudgetWeb/blob/main/img/BudgetWeb.png)

- css/frame.css (CSS for the main frame of the website)
- css/controls.css (CSS for control elements that do not require JavaScript)
- css/widgets.css (CSS for widgets that require JavaScript)
- js/widgets.js (JavaScript for widgets)
- js/util.js (JavaScript for general utility functions)
- js/menu.js (JavaScript for loading the menu bar)
- js/footer.js (JavaScript for loading the footer)

### Uses jQuery to load the menu bar and the footer, as shown below:
```html
<script src="js/menu.js"></script>
<script src="js/footer.js"></script>
```
The `menu.js` script loads `menu.html` to `menu-container`.
```html
<div class="menu-container"></div>
```
The `footer.js` script loads `footer.html` to `footer-container`.
```html
<div class="footer-container"></div>
```

### This template is tested and worked on:
- macOS 12.4
  - Chrome 103
  - Safari 15.5
  - Firefox 103
  - Edge 103
- Android 12
  - Chrome 103
- iOS 15.5
  - Chrome 103
  - Safari 15.5
  - Firefox 102
 
  - 

# Overview
![](https://github.com/KarmaScripter/BudgetWeb/blob/main/etc/github/Overview.gif)


