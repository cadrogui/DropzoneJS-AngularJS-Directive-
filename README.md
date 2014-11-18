# AngularJS Directive for Dropzone.js

Dropzone.js is a usefull javascript library for upload content to the server, this repo has a complete implementation of this library on angularjs, using a directive.

the usage is very simple, you only need to copy the directive and the config object ( the object is in the controller), and in your view you insert this:

```
<drop-zone></drop-zone>
```

If you want use this directive with a CakePHP (as a REST Service), you may need use a input type hidden field to add extra data.

in CakePHP you must get the data like this:

For get the uploaded file data:

```
$this->params["form"]
```

For get the hidden fields data:

```
$this->request["data"]
```
