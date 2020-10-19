## Feature


## Installation
Fork this project and use it in your website.

[OR]

You can also use this using GitHub via cdnjs
```
<script src="https://cdn.jsdelivr.net/gh/vigneshksaithal/bootstrap-autocomplete@1.0.0/cdn/index.js" integrity="sha384-IEcBGr1njXrPGB6q5LWdWuYaj5Uz0O26Ndmqf9TfH4/va9Xv0FdeQe4IgNqpRlZ3" crossorigin="anonymous"></script>
```
## Usage
The JavaScript component consists of a root container element, div with **ID: autocomplete** and an input element.
```
<div id="autocomplete">
  <input **id="search"** type="text" class="form-contorol"/>
</div>
```
### Initiate the autocomplete function once
Pass the search(input) element and the array of values.
'''
<script>
  var arr = ['apple', 'mango', 'grapes'];
  var search = document.getElementById('search');
  autocomplete(search, arr);
</script>
```

Support or Contact
