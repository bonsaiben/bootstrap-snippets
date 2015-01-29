Bootstrap Snippets
==================

Work in progress

HTML and Haml snippet files for [Twitter Bootstrap 3.3.2](http://getbootstrap.com/), for the [snipmate](https://github.com/garbas/vim-snipmate) plugin for Vim.

Dependencies
------------

- [vim-snipmate](https://github.com/garbas/vim-snipmate)

How to install
--------------

- Install [vim-snipmate](https://github.com/garbas/vim-snipmate) and dependencies
- Install bootstrap-snippets

Installation using [Pathogen](https://github.com/tpope/vim-pathogen)
---------------------------

    $ cd ~/.vim
    $ mkdir bundle
    $ cd bundle
    $ git clone git://github.com/bonsaiben/bootstrap-snippets.git

    # Install dependencies:
    $ git clone https://github.com/garbas/vim-snipmate.git
    $ git clone https://github.com/tomtom/tlib_vim.git
    $ git clone https://github.com/MarcWeber/vim-addon-mw-utils.git

Usage
-----

Generally the snippet trigger will be the name of the relevant class or combination of classes (no hyphens).

For example, `btnprimary` becomes:

    <button type="button" class="btn btn-primary">${1:Default}</button>

See the full trigger glossary below.


# Getting started

## Bootstrap CDN

`bootstrapcdn`

```html
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">

<!-- Optional theme -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css">

<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
```

## Basic template

`basictemplate`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap 101 Template</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
```

# CSS

## HTML5 doctype

`html5`

```html
<!DOCTYPE html>
<html lang="en">
  ...
</html>
```

## Mobile first

`viewport`

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

`viewportnozoom`

```html
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
```

## Containers

`container`

```html
<div class="container">
  ...
</div>
```

`containerfluid`

```html
<div class="container-fluid">
  ...
</div>
```

## Grid system

`row`

```html
<div class="row">
  ...
</div>
```

`colxs`

```html
<div class="col-xs-...">
  ...
</div>
```

`colsm`

```html
<div class="col-sm-...">
  ...
</div>
```

`colmd`

```html
<div class="col-md-...">
  ...
</div>
```

`collg`

```html
<div class="col-lg-...">
  ...
</div>
```

`colxsoffset`

```html
<div class="col-xs-offset-...">
  ...
</div>
```

`colsmoffset`

```html
<div class="col-sm-offset-...">
  ...
</div>
```

`colmdoffset`

```html
<div class="col-md-offset-...">
  ...
</div>
```

`collgoffset`

```html
<div class="col-lg-offset-...">
  ...
</div>
```

`colxspush`

```html
<div class="col-xs-push-...">
  ...
</div>
```

`colsmpush`

```html
<div class="col-sm-push-...">
  ...
</div>
```

`colmdpush`

```html
<div class="col-md-push-...">
  ...
</div>
```

`collgpush`

```html
<div class="col-lg-push-...">
  ...
</div>
```

`colxspull`

```html
<div class="col-xs-pull-...">
  ...
</div>
```

`colsmpull`

```html
<div class="col-sm-pull-...">
  ...
</div>
```

`colmdpull`

```html
<div class="col-md-pull-...">
  ...
</div>
```

`collgpull`

```html
<div class="col-lg-pull-...">
  ...
</div>
```

## Typography

`h1`

```html
<h1>...</h1>
```

`h2`

```html
<h2>...</h2>
```

`h3`

```html
<h3>...</h3>
```

`h4`

```html
<h4>...</h4>
```

`h5`

```html
<h5>...</h5>
```

`h6`

```html
<h6>...</h6>
```


`h1small`

```html
<h1>... <small>...</small></h1>
```

`h2small`

```html
<h2>... <small>...</small></h2>
```

`h3small`

```html
<h3>... <small>...</small></h3>
```

`h4small`

```html
<h4>... <small>...</small></h4>
```

`h5small`

```html
<h5>... <small>...</small></h5>
```

`h6small`

```html
<h6>... <small>...</small></h6>
```

`p`

```html
<p>...</p>
```

`lead`

```html
<p class="lead">...</p>
```

`mark`

```html
<mark>...</mark>
```

`del`

```html
<del>...</del>
```

`s`

```html
<s>...</s>
```

`ins`

```html
<ins>...</ins>
```

`u`

```html
<u>...</u>
```

`small`

```html
<small>...</small>
```

`strong`

```html
<strong>...</strong>
```

`em`

```html
<em>...</em>
```

`textleft`

```html
<p class="text-left">...</p>
```

`textcenter`

```html
<p class="text-center">...</p>
```

`textright`

```html
<p class="text-right">...</p>
```

`textjustify`

```html
<p class="text-justify">...</p>
```

`textnowrap`

```html
<p class="text-nowrap">...</p>
```


`textlowercase`

```html
<p class="text-lowercase">...</p>
```

`textuppercase`

```html
<p class="text-uppercase">...</p>
```

`textcapitalize`

```html
<p class="text-capitalize">...</p>
```

`abbr`

```html
<abbr title="...">...</abbr>
```


`initialism`

```html
<abbr title="..." class="initialism">...</abbr>
```

`address`

```html
<address>
  <strong>Twitter, Inc.</strong><br>
  795 Folsom Ave, Suite 600<br>
  San Francisco, CA 94107<br>
  <abbr title="Phone">P:</abbr> (123) 456-7890
</address>

<address>
  <strong>Full Name</strong><br>
  <a href="mailto:#">first.last@example.com</a>
</address>
```

`blockquote`

```html
<blockquote>
  <p>...</p>
</blockquote>
```

`blockquotesource`

```html
<blockquote>
  <p>...</p>
  <footer>... <cite title="...">...</cite></footer>
</blockquote>
```

`blockquotereverse`

```html
<blockquote class="blockquote-reverse">
  ...
</blockquote>
```

`ul`

```html
<ul>
  <li>...</li>
</ul>
```

`ol`

```html
<ol>
  <li>...</li>
</ol>
```

`listunstyled`

```html
<ul class="list-unstyled">
  <li>...</li>
</ul>
```

`listinline`

```html
<ul class="list-inline">
  <li>...</li>
</ul>
```

`dl`

```html
<dl>
  <dt>...</dt>
  <dd>...</dd>
</dl>
```

`dlhorizontal`

```html
<dl class="dl-horizontal">
  <dt>...</dt>
  <dd>...</dd>
</dl>
```


## Code

`code`

```html
<code>...</code>
```

`kbd`

```html
<kbd>...</kbd>
```

`pre`

```html
<pre>...</pre>
```

`var`

```html
<var>...</var>
```


`samp`

```html
<samp>...</samp>
```


## Tables

`table`

```html
<table class="table">
  ...
</table>
```

`tablestriped`

```html
<table class="table table-striped">
  ...
</table>
```

`tablebordered`

```html
<table class="table table-bordered">
  ...
</table>
```

`tablehover`

```html
<table class="table table-hover">
  ...
</table>
```

`tablecondensed`

```html
<table class="table table-condensed">
  ...
</table>
```


`tractive`

```html
<tr class="active">...</tr>
```

`trsuccess`

```html
<tr class="success">...</tr>
```

`trwarning`

```html
<tr class="warning">...</tr>
```

`trdanger`

```html
<tr class="danger">...</tr>
```

`trinfo`

```html
<tr class="info">...</tr>
```


`tdactive`

```html
<td class="active">...</td>
```

`tdsuccess`

```html
<td class="success">...</td>
```

`tdwarning`

```html
<td class="warning">...</td>
```

`tddanger`

```html
<td class="danger">...</td>
```

`tdinfo`

```html
<td class="info">...</td>
```


`thactive`

```html
<th class="active">...</th>
```

`thsuccess`

```html
<th class="success">...</th>
```

`thwarning`

```html
<th class="warning">...</th>
```

`thdanger`

```html
<th class="danger">...</th>
```

`thinfo`

```html
<th class="info">...</th>
```

`tableresponsive`

```html
<div class="table-responsive">
  <table class="table">
    ...
  </table>
</div>
```


## Forms

`form`

```html
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Enter email">
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <div class="form-group">
    <label for="exampleInputFile">File input</label>
    <input type="file" id="exampleInputFile">
    <p class="help-block">Example block-level help text here.</p>
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox"> Check me out
    </label>
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>
```

`forminline`

```html
<form class="form-inline">
  <div class="form-group">
    <label class="sr-only" for="exampleInputEmail3">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail3" placeholder="Enter email">
  </div>
  <div class="form-group">
    <label class="sr-only" for="exampleInputPassword3">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword3" placeholder="Password">
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox"> Remember me
    </label>
  </div>
  <button type="submit" class="btn btn-default">Sign in</button>
</form>
```

`formhorizontal`

```html
<form class="form-horizontal">
  <div class="form-group">
    <label for="inputEmail3" class="col-sm-2 control-label">Email</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" placeholder="Email">
    </div>
  </div>
  <div class="form-group">
    <label for="inputPassword3" class="col-sm-2 control-label">Password</label>
    <div class="col-sm-10">
      <input type="password" class="form-control" id="inputPassword3" placeholder="Password">
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <div class="checkbox">
        <label>
          <input type="checkbox"> Remember me
        </label>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-offset-2 col-sm-10">
      <button type="submit" class="btn btn-default">Sign in</button>
    </div>
  </div>
</form>
```

`input`

```html
<input type="text" class="form-control" placeholder="Text input">
```

`textarea`

```html
<textarea class="form-control" rows="3"></textarea>
```

`checkbox`

```html
<div class="checkbox">
  <label>
    <input type="checkbox" value="">
    Option one is this and that&mdash;be sure to include why it's great
  </label>
</div>
<div class="checkbox disabled">
  <label>
    <input type="checkbox" value="" disabled>
    Option two is disabled
  </label>
</div>
```

`radio`

```html
<div class="radio">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios1" value="option1" checked>
    Option one is this and that&mdash;be sure to include why it's great
  </label>
</div>
<div class="radio">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios2" value="option2">
    Option two can be something else and selecting it will deselect option one
  </label>
</div>
<div class="radio disabled">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios3" value="option3" disabled>
    Option three is disabled
  </label>
</div>
```

`checkboxinline`

```html
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox1" value="option1"> 1
</label>
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox2" value="option2"> 2
</label>
<label class="checkbox-inline">
  <input type="checkbox" id="inlineCheckbox3" value="option3"> 3
</label>
```

`radioinline`

```html
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1"> 1
</label>
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2"> 2
</label>
<label class="radio-inline">
  <input type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3"> 3
</label>
```

`select`

```html
<select class="form-control">
  <option>1</option>
  <option>2</option>
  <option>3</option>
  <option>4</option>
  <option>5</option>
</select>
```

`selectmultiple`

```html
<select multiple class="form-control">
  <option>1</option>
  <option>2</option>
  <option>3</option>
  <option>4</option>
  <option>5</option>
</select>
```

`formcontrolstatic`

```html
<div class="form-group">
  <label class="col-sm-2 control-label">Email</label>
  <div class="col-sm-10">
    <p class="form-control-static">email@example.com</p>
  </div>
</div>
```

`inputdisabled`

```html
<input class="form-control" id="disabledInput" type="text" placeholder="Disabled input here..." disabled>
```

`fieldsetdisabled`

```html
<fieldset disabled>
  <div class="form-group">
    <label for="disabledTextInput">Disabled input</label>
    <input type="text" id="disabledTextInput" class="form-control" placeholder="Disabled input">
  </div>
  <div class="form-group">
    <label for="disabledSelect">Disabled select menu</label>
    <select id="disabledSelect" class="form-control">
      <option>Disabled select</option>
    </select>
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox"> Can't check this
    </label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</fieldset>
```

`inputreadonly`

```html
<input class="form-control" type="text" placeholder="Readonly input here…" readonly>
```

`formgrouphassuccess`

```html
<div class="form-group has-success">
  <label class="control-label" for="inputSuccess1">Input with success</label>
  <input type="text" class="form-control" id="inputSuccess1">
</div>
```

`formgrouphaswarning`

```html
<div class="form-group has-warning">
  <label class="control-label" for="inputWarning1">Input with warning</label>
  <input type="text" class="form-control" id="inputWarning1">
</div>
```

`formgrouphaserror`

```html
<div class="form-group has-error">
  <label class="control-label" for="inputError1">Input with error</label>
  <input type="text" class="form-control" id="inputError1">
</div>
```

`checkboxhassuccess`

```html
<div class="has-success">
  <div class="checkbox">
    <label>
      <input type="checkbox" id="checkboxSuccess" value="option1">
      Checkbox with success
    </label>
  </div>
</div>
```

`checkboxhaswarning`

```html
<div class="has-warning">
  <div class="checkbox">
    <label>
      <input type="checkbox" id="checkboxWarning" value="option1">
      Checkbox with warning
    </label>
  </div>
</div>
```

`checkboxhaserror`

```html
<div class="has-error">
  <div class="checkbox">
    <label>
      <input type="checkbox" id="checkboxError" value="option1">
      Checkbox with error
    </label>
  </div>
</div>
```


`formgrouphasfeedback`

```html
<div class="form-group has-success has-feedback">
  <label class="control-label" for="inputGroupSuccess1">Input group with success</label>
  <div class="input-group">
    <span class="input-group-addon">@</span>
    <input type="text" class="form-control" id="inputGroupSuccess1" aria-describedby="inputGroupSuccess1Status">
  </div>
  <span class="glyphicon glyphicon-ok form-control-feedback" aria-hidden="true"></span>
  <span id="inputGroupSuccess1Status" class="sr-only">(success)</span>
</div>
```

`inputlg`

```html
<input class="form-control input-lg" type="text" placeholder=".input-lg">
```

`inputsm`

```html
<input class="form-control input-sm" type="text" placeholder=".input-sm">
```

`selectlg`

```html
<select class="form-control input-lg">...</select>
```

`selectsm`

```html
<select class="form-control input-sm">...</select>
```

`formgrouplg`

```html
<div class="form-group form-group-lg">
  <label class="col-sm-2 control-label" for="formGroupInputLarge">Large label</label>
  <div class="col-sm-10">
    <input class="form-control" type="text" id="formGroupInputLarge" placeholder="Large input">
  </div>
</div>
```

`formgroupsm`

```html
<div class="form-group form-group-sm">
  <label class="col-sm-2 control-label" for="formGroupInputSmall">Small label</label>
  <div class="col-sm-10">
    <input class="form-control" type="text" id="formGroupInputSmall" placeholder="Small input">
  </div>
</div>
```

`inputhelpblock`

```html
<label class="sr-only" for="inputHelpBlock">Input with help text</label>
<input type="text" id="inputHelpBlock" class="form-control" aria-describedby="helpBlock">
...
<span id="helpBlock" class="help-block">A block of help text that breaks onto a new line and may extend beyond one line.</span>
```


## Buttons


`btn`

```html
<button class="btn btn-default" type="submit">Button</button>
```

`abtn`

```html
<a class="btn btn-default" href="#" role="button">Link</a>
```

`inputbtn`

```html
<input class="btn btn-default" type="button" value="Input">
```

`submitbtn`

```html
<input class="btn btn-default" type="submit" value="Submit">
```


`btndefault`

```html
<button type="button" class="btn btn-default">Default</button>
```

`abtndefault`

```html
<a href="#" class="btn btn-default" role="button">Default</a>
```

`btnprimary`

```html
<button type="button" class="btn btn-primary">Primary</button>
```

`abtnprimary`

```html
<a href="#" class="btn btn-primary" role="button">Primary</a>
```

`btnsuccess`

```html
<button type="button" class="btn btn-success">Success</button>
```

`abtnsuccess`

```html
<a href="#" class="btn btn-success" role="button">Success</a>
```

`btninfo`

```html
<button type="button" class="btn btn-info">Info</button>
```

`abtninfo`

```html
<a href="#" class="btn btn-info" role="button">Info</a>
```

`btnwarning`

```html
<button type="button" class="btn btn-warning">Warning</button>
```

`abtnwarning`

```html
<a href="#" class="btn btn-warning" role="button">Warning</a>
```

`btndanger`

```html
<button type="button" class="btn btn-danger">Danger</button>
```

`abtndanger`

```html
<a href="#" class="btn btn-danger" role="button">Danger</a>
```

`btnlink`

```html
<button type="button" class="btn btn-link">Link</button>
```

`abtnlink`

```html
<a href="#" class="btn btn-link" role="button">Link</a>
```


`btnlg`

```html
<button type="button" class="btn btn-default btn-lg">Large button</button>
```

`abtnlg`

```html
<a href="#" class="btn btn-default btn-lg" role="button">Large button</a>
```

`btnsm`

```html
<button type="button" class="btn btn-default btn-sm">Small button</button>
```

`abtnsm`

```html
<a href="#" class="btn btn-default btn-sm" role="button">Small button</a>
```

`btnxs`

```html
<button type="button" class="btn btn-default btn-xs">Extra small button</button>
```

`abtnxs`

```html
<a href="#" class="btn btn-default btn-xs" role="button">Extra small button</a>
```

`btnblock`

```html
<button type="button" class="btn btn-default btn-block">Block level button</button>
```

`abtnblock`

```html
<a href="#" class="btn btn-default btn-block" role="button">Block level button</a>
```

`btnactive`

```html
<button type="button" class="btn btn-default active">Button</button>
```

`abtnactive`

```html
<a href="#" class="btn btn-default active" role="button">Link</a>
```

`btndisabled`

```html
<button type="button" class="btn btn-default" disabled="disabled">Button</button>
```

`abtndisabled`

```html
<a href="#" class="btn btn-default disabled" role="button">Link</a>
```


## Images

`imgresponsive`

```html
<img src="..." class="img-responsive" alt="Responsive image">
```

`imgrounded`

```html
<img src="..." alt="..." class="img-rounded">
```

`imgcircle`

```html
<img src="..." alt="..." class="img-circle">
```

`imgthumbnail`

```html
<img src="..." alt="..." class="img-thumbnail">
```


## Helper classes

`textmuted`

```html
<p class="text-muted">...</p>
```

`textprimary`

```html
<p class="text-primary">...</p>
```

`textsuccess`

```html
<p class="text-success">...</p>
```

`textinfo`

```html
<p class="text-info">...</p>
```

`textwarning`

```html
<p class="text-warning">...</p>
```

`textdanger`

```html
<p class="text-danger">...</p>
```


`bgprimary`

```html
<p class="bg-primary">...</p>
```

`bgsuccess`

```html
<p class="bg-success">...</p>
```

`bginfo`

```html
<p class="bg-info">...</p>
```

`bgwarning`

```html
<p class="bg-warning">...</p>
```

`bgdanger`

```html
<p class="bg-danger">...</p>
```

`close`

```html
<button type="button" class="close" aria-label="Close"><span aria-hidden="true">&times;</span></button>
```

`caret`

```html
<span class="caret"></span>
```


`pullleft`

```html
<div class="pull-left">...</div>
```

`pullright`

```html
<div class="pull-right">...</div>
```

`centerblock`

```html
<div class="center-block">...</div>
```

`clearfix`

```html
<div class="clearfix">...</div>
```


`show`

```html
<div class="show">...</div>
```

`hidden`

```html
<div class="hidden">...</div>
```

`invisible`

```html
<div class="invisible">...</div>
```

`sronlyfocusable`

```html
<a class="sr-only sr-only-focusable" href="#content">Skip to main content</a>
```

`texthide`

```html
<h1 class="text-hide">Custom heading</h1>
```


`hiddenxs`

```html
<div class="hidden-xs"></div>
```

`hiddensm`

```html
<div class="hidden-sm"></div>
```

`hiddenmd`

```html
<div class="hidden-md"></div>
```

`hiddenlg`

```html
<div class="hidden-lg"></div>
```

`visiblexsblock`

```html
<div class="visible-xs-block"></div>
```

`visiblexsinline`

```html
<div class="visible-xs-inline"></div>
```

`visiblexsinlineblock`

```html
<div class="visible-xs-inline-block"></div>
```

`visiblesmblock`

```html
<div class="visible-sm-block"></div>
```

`visiblesminline`

```html
<div class="visible-sm-inline"></div>
```

`visiblesminlineblock`

```html
<div class="visible-sm-inline-block"></div>
```

`visiblemdblock`

```html
<div class="visible-md-block"></div>
```

`visiblemdinline`

```html
<div class="visible-md-inline"></div>
```

`visiblemdinlineblock`

```html
<div class="visible-md-inline-block"></div>
```

`visiblelgblock`

```html
<div class="visible-lg-block"></div>
```

`visiblelginline`

```html
<div class="visible-lg-inline"></div>
```

`visiblelginlineblock`

```html
<div class="visible-lg-inline-block"></div>
```

`visibleprintblock`

```html
<div class="visible-print-block"></div>
```

`visibleprintinline`

```html
<div class="visible-print-inline"></div>
```

`visibleprintinlineblock`

```html
<div class="visible-print-inline-block"></div>
```

`hiddenprint`

```html
<div class="hidden-print"></div>
```

