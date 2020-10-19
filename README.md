# bootstrap-autocomplete
## Features
- **1.8kb minified**
- **Pure Vanilla JavaScript**
- **Only bootstrap CSS Required**

## Installation
Fork this repository and use it in your website.
<a id="raw-url" href="https://github.com/vigneshksaithal/bootstrap-autocomplete">Fork It</a>

[OR]

You can also use this by adding the below code to your website.
```
<script src="https://cdn.jsdelivr.net/gh/vigneshksaithal/bootstrap-autocomplete@1.0.0/src/index.min.js"></script>
```
## Usage
1. Add javascript to your web app.
```
<script src="/bootstrap-autocomplete.min.js"></script>
```
[OR]
Directly add jsDelivr CDN provided below.
```
<script src="https://cdn.jsdelivr.net/gh/vigneshksaithal/bootstrap-autocomplete@1.0.0/src/index.min.js"></script>
```
2. Add HTML code.
```
<div id="autocomplete">
  <input id="search" type="text" class="form-contorol"/>
</div>
```
3. Initiate the autocomplete function.
Pass the search(input) element and the array of values.

```
<script>
  var arr = ['apple', 'mango', 'grapes'];
  var search = document.getElementById('search');
  autocomplete(search, arr);
</script>
```
## Contributions
If you find any bugs or have any feature requests then just raise a issue.
Thanks You🙏
