webjars-angular-datatables
==========================

Webjar integration of angular-datatables(http://l-lin.github.io/angular-datatables)

Installation
------------

Include the JS file in your `index.html` file:

```html
<script src="/webjars/angular-datatables/0.0.3/angular-datatables.min.js"></script>
```

**IMPORTANT**: You must include the JS **AFTER** `jQuery` and `DataTables`!

If you want the `Twitter Bootstrap` support, then add the CSS file:

```html
<link rel="stylesheet" href="/webjars/angular-datatables/0.0.3/datatables.bootstrap.min.css">
```

Declare dependencies on your module app like this:

```html
angular.module('myModule', ['datatables']);
```

Complete example
----------------

```
<link rel="stylesheet" href="/webjars/datatables/1.10.1/css/jquery.dataTables.min.css">
<!--optionnal-->
<link rel="stylesheet" href="/webjars/angular-datatables/0.0.3/datatables.bootstrap.min.css">

<script src="/webjars/jquery/1.11.1/jquery.min.js"></script>
<script src="/webjars/datatables/1.10.1/js/jquery.dataTables.min.js"></script>
<!-- needs to be included AFTER jQuery and Datatables -->
<script src="/webjars/angular-datatables/0.0.3/angular-datatables.min.js"></script>
```


Usage
-----

See [github page](https://l-lin.github.io/angular-datatables).
