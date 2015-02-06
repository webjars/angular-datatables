webjars-angular-datatables
==========================

Webjar integration of angular-datatables(http://l-lin.github.io/angular-datatables)

Installation
------------

Include the JS file in your `index.html` file:

```html
<script src="/webjars/angular-datatables/0.4.0/angular-datatables.min.js"></script>
```

**IMPORTANT**: You must include the JS **AFTER** `jQuery` and `DataTables`!

With RequireJS/AMD, this is

```javascript
// Load webjars config script first. See http://www.webjars.org/documentation

require(['jquery', 'datatables', 'angular', 'angular-datatables'], function() {...});
```

If you want the `Twitter Bootstrap` support, then add the CSS file:

```html
<link rel="stylesheet" href="/webjars/angular-datatables/0.4.0/plugins/bootstrap/datatables.bootstrap.css">
```

NOTE: The path changed in v0.4.0. To load this with the require-css plug-in use `css!angular-datatables.bootstrap-css`.


Declare dependencies on your module app like this:

```javascript
angular.module('myModule', ['datatables']);
```

Complete example
----------------

```
<link rel="stylesheet" href="/webjars/datatables/1.10.1/css/jquery.dataTables.min.css">
<!--optionnal-->
<link rel="stylesheet" href="/webjars/angular-datatables/0.4.0/plugins/bootstrap/datatables.bootstrap.css">

<script src="/webjars/jquery/1.11.1/jquery.min.js"></script>
<script src="/webjars/datatables/1.10.1/js/jquery.dataTables.min.js"></script>
<!-- needs to be included AFTER jQuery and Datatables -->
<script src="/webjars/angular-datatables/0.4.0/angular-datatables.min.js"></script>
```


Usage
-----

See [angular datatables website](https://l-lin.github.io/angular-datatables).

Plug-ins
--------
See the pom.xml file for the exported plug-ins.

columnfilter, scroller and tabletools did not have usable Webjars at the time of writing. They will needed to be configured externally if RequireJS is used.
