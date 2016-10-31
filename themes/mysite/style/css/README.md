# `style/css` Directory
The `style/css` directory contains all compiled CSS for your theme. 
This is where the actual styles live that are loaded when this theme is used to render a Drupal page.
Note the relevant portion of `mysite.libraries.yml`:

```
mysite:
  js:
    js/mysite.js: {}
  css:
    theme:
      style/css/mysite.css: {}
```
