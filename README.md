x-tabs
========

Tab box with navigation

Usage
-----
* Import the `x-tab.html` and `the x-tabs.html` into your application
* Insert a `<x-tabs>` tag with `<x-tab>` tags for each tab.

Example:

```html
<!doctype html>
<html>
<head>
  <title>x-tabs demo</title>
  <link rel="import" href="x-tabs.html" />
  <link rel="import" href="x-tab.html" />
</head>
<body>
  <h1>x-tabs demo</h1>
  <x-tabs>
    <x-tab label="First tab">
      <img src="http://placekitten.com/g/500/500" alt="A kitty" />
    </x-tab>

    <x-tab label="Second tab">
      <div>Lorem ipsum dolorem sit amet...</div>
    </x-tab>
  </x-tabs>
</body>
</html>
```
