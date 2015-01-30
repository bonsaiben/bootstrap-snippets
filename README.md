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


# Components

## Glyphicons

`glyphicon`

```html
<span class="glyphicon glyphicon-..." aria-hidden="true"></span>
```

## Dropdowns

`dropdown`

```html
<div class="dropdown">
  <button class="btn btn-default dropdown-toggle" type="button" id="dropdownMenu1" data-toggle="dropdown" aria-expanded="true">
    Dropdown
    <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Action</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Another action</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Something else here</a></li>
    <li role="presentation"><a role="menuitem" tabindex="-1" href="#">Separated link</a></li>
  </ul>
</div>
```

`dropdownmenuright`

```html
<ul class="dropdown-menu dropdown-menu-right" role="menu" aria-labelledby="dLabel">
  ...
</ul>
```

`dropdownheader`

```html
<li role="presentation" class="dropdown-header">...</li>
```

`divider`

```html
<li role="presentation" class="divider"></li>
```

`lidisabled`

```html
<li role="presentation" class="disabled"><a role="menuitem" tabindex="-1" href="#">...</a></li>
```

## Button groups

`btngroup`

```html
<div class="btn-group" role="group" aria-label="...">
  <button type="button" class="btn btn-default">Left</button>
  <button type="button" class="btn btn-default">Middle</button>
  <button type="button" class="btn btn-default">Right</button>
</div>
```

`abtngroup`

```html
<div class="btn-group" role="group" aria-label="...">
  <a class="btn btn-default" href="#" role="button">Left</a>
  <a class="btn btn-default" href="#" role="button">Middle</a>
  <a class="btn btn-default" href="#" role="button">Right</a>
</div>
```

`btntoolbar`

```html
<div class="btn-toolbar" role="toolbar" aria-label="...">
  <div class="btn-group" role="group" aria-label="...">...</div>
  <div class="btn-group" role="group" aria-label="...">...</div>
  <div class="btn-group" role="group" aria-label="...">...</div>
</div>
```

`btngrouplg`

```html
<div class="btn-group btn-group-lg" role="group" aria-label="...">...</div>
```

`btngroupsm`

```html
<div class="btn-group btn-group-sm" role="group" aria-label="...">...</div>
```

`btngroupxs`

```html
<div class="btn-group btn-group-xs" role="group" aria-label="...">...</div>
```

`btngroupvertical`

```html
<div class="btn-group-vertical" role="group" aria-label="...">
  ...
</div>
```

`btngroupjustified`

```html
<div class="btn-group btn-group-justified" role="group" aria-label="...">
  <div class="btn-group" role="group">
    <button type="button" class="btn btn-default">Left</button>
  </div>
  <div class="btn-group" role="group">
    <button type="button" class="btn btn-default">Middle</button>
  </div>
  <div class="btn-group" role="group">
    <button type="button" class="btn btn-default">Right</button>
  </div>
</div>
```

`abtngroupjustified`

```html
<div class="btn-group btn-group-justified" role="group" aria-label="...">
  <a class="btn btn-default" href="#" role="button">Left</a>
  <a class="btn btn-default" href="#" role="button">Middle</a>
  <a class="btn btn-default" href="#" role="button">Right</a>
</div>
```

## Button dropdowns

`btndropdown`

```html
<div class="btn-group">
  <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
    Action <span class="caret"></span>
  </button>
  <ul class="dropdown-menu" role="menu">
    <li><a href="#">Action</a></li>
    <li><a href="#">Another action</a></li>
    <li><a href="#">Something else here</a></li>
    <li class="divider"></li>
    <li><a href="#">Separated link</a></li>
  </ul>
</div>
```

`btndropdownsplit`

```html
<div class="btn-group">
  <button type="button" class="btn btn-danger">Action</button>
  <button type="button" class="btn btn-danger dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
    <span class="caret"></span>
    <span class="sr-only">Toggle Dropdown</span>
  </button>
  <ul class="dropdown-menu" role="menu">
    <li><a href="#">Action</a></li>
    <li><a href="#">Another action</a></li>
    <li><a href="#">Something else here</a></li>
    <li class="divider"></li>
    <li><a href="#">Separated link</a></li>
  </ul>
</div>
```

`btndropup`

```html
<div class="btn-group dropup">
  <button type="button" class="btn btn-default">Dropup</button>
  <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
    <span class="caret"></span>
    <span class="sr-only">Toggle Dropdown</span>
  </button>
  <ul class="dropdown-menu" role="menu">
    <!-- Dropdown menu links -->
  </ul>
</div>
```

## Input groups

`inputgroup`

```html
<div class="input-group">
  <span class="input-group-addon">$</span>
  <input type="text" class="form-control" aria-label="Amount (to the nearest dollar)">
  <span class="input-group-addon">.00</span>
</div>
```

`inputgrouplg`

```html
<div class="input-group input-group-lg">
  <span class="input-group-addon" id="sizing-addon1">@</span>
  <input type="text" class="form-control" placeholder="Username" aria-describedby="sizing-addon1">
</div>
```

`inputgroupsm`

```html
<div class="input-group input-group-sm">
  <span class="input-group-addon" id="sizing-addon3">@</span>
  <input type="text" class="form-control" placeholder="Username" aria-describedby="sizing-addon3">
</div>
```

`inputgroupcheckbox`

```html
<div class="input-group">
  <span class="input-group-addon">
    <input type="checkbox" aria-label="...">
  </span>
  <input type="text" class="form-control" aria-label="...">
</div>
```

`inputgroupradio`

```html
<div class="input-group">
  <span class="input-group-addon">
    <input type="radio" aria-label="...">
  </span>
  <input type="text" class="form-control" aria-label="...">
</div>
```

`inputgroupbtn`

```html
<div class="input-group">
  <input type="text" class="form-control" placeholder="Search for...">
  <span class="input-group-btn">
    <button class="btn btn-default" type="button">Go!</button>
  </span>
</div>
```

`inputgroupbtndropdown`

```html
<div class="input-group">
  <input type="text" class="form-control" aria-label="...">
  <div class="input-group-btn">
    <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-expanded="false">Action <span class="caret"></span></button>
    <ul class="dropdown-menu dropdown-menu-right" role="menu">
      <li><a href="#">Action</a></li>
      <li><a href="#">Another action</a></li>
      <li><a href="#">Something else here</a></li>
      <li class="divider"></li>
      <li><a href="#">Separated link</a></li>
    </ul>
  </div><!-- /btn-group -->
</div>
```

`inputgroupbtndropdownsplit`

```html
<div class="input-group">
  <input type="text" class="form-control" aria-label="...">
  <div class="input-group-btn">
    <!-- Button and dropdown menu -->
  </div>
</div>
```


## Navs

`navtabs`

```html
<ul class="nav nav-tabs">
  <li role="presentation" class="active"><a href="#">Home</a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages</a></li>
</ul>
```

`navpills`

```html
<ul class="nav nav-pills">
  <li role="presentation" class="active"><a href="#">Home</a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages</a></li>
</ul>
```

`navpillsstacked`

```html
<ul class="nav nav-pills nav-stacked">
  ...
</ul>
```

`navtabsjustified`

```html
<ul class="nav nav-tabs nav-justified">
  ...
</ul>
```

`navpillsjustified`

```html
<ul class="nav nav-pills nav-justified">
  ...
</ul>
```

`navtabsdropdown`

```html
<ul class="nav nav-tabs">
  ...
  <li role="presentation" class="dropdown">
    <a class="dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-expanded="false">
      Dropdown <span class="caret"></span>
    </a>
    <ul class="dropdown-menu" role="menu">
      ...
    </ul>
  </li>
  ...
</ul>
```

`navpillsdropdown`

```html
<ul class="nav nav-pills">
  ...
  <li role="presentation" class="dropdown">
    <a class="dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-expanded="false">
      Dropdown <span class="caret"></span>
    </a>
    <ul class="dropdown-menu" role="menu">
      ...
    </ul>
  </li>
  ...
</ul>
```



## Navbar

`navbar`

```html
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Brand</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu" role="menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li class="divider"></li>
            <li><a href="#">Separated link</a></li>
            <li class="divider"></li>
            <li><a href="#">One more separated link</a></li>
          </ul>
        </li>
      </ul>
      <form class="navbar-form navbar-left" role="search">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Search">
        </div>
        <button type="submit" class="btn btn-default">Submit</button>
      </form>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu" role="menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li class="divider"></li>
            <li><a href="#">Separated link</a></li>
          </ul>
        </li>
      </ul>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
```

`navbarform`

```html
<form class="navbar-form navbar-left" role="search">
  <div class="form-group">
    <input type="text" class="form-control" placeholder="Search">
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>
```

`navbarbtn`

```html
<button type="button" class="btn btn-default navbar-btn">Sign in</button>
```

`navbartext`

```html
<p class="navbar-text">Signed in as Mark Otto</p>
```

`navbarlink`

```html
<a href="#" class="navbar-link">Mark Otto</a>
```

`navbarfixedtop`

```html
<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    ...
  </div>
</nav>
```

`navbarfixedbottom`

```html
<nav class="navbar navbar-default navbar-fixed-bottom">
  <div class="container">
    ...
  </div>
</nav>
```

`navbarstatictop`

```html
<nav class="navbar navbar-default navbar-static-top">
  <div class="container">
    ...
  </div>
</nav>
```

`navbarinverse`

```html
<nav class="navbar navbar-inverse">
  ...
</nav>
```



## Breadcrumbs

`breadcrumb`

```html
<ol class="breadcrumb">
  <li><a href="#">Home</a></li>
  <li><a href="#">Library</a></li>
  <li class="active">Data</li>
</ol>
```


## Pagination

`pagination`

```html
<nav>
  <ul class="pagination">
    <li class="disabled">
      <a href="#" aria-label="Previous">
        <span aria-hidden="true">&laquo;</span>
      </a>
    </li>
    <li class="active"><a href="#">1</a></li>
    <li><a href="#">2</a></li>
    <li><a href="#">3</a></li>
    <li><a href="#">4</a></li>
    <li><a href="#">5</a></li>
    <li>
      <a href="#" aria-label="Next">
        <span aria-hidden="true">&raquo;</span>
      </a>
    </li>
  </ul>
</nav>
```

`paginationlg`

```html
<nav><ul class="pagination pagination-lg">...</ul></nav>
```

`paginationsm`

```html
<nav><ul class="pagination pagination-sm">...</ul></nav>
```

`pager`

```html
<nav>
  <ul class="pager">
    <li><a href="#">Previous</a></li>
    <li><a href="#">Next</a></li>
  </ul>
</nav>
```

`pageraligned`

```html
<nav>
  <ul class="pager">
    <li class="previous"><a href="#"><span aria-hidden="true">&larr;</span> Older</a></li>
    <li class="next"><a href="#">Newer <span aria-hidden="true">&rarr;</span></a></li>
  </ul>
</nav>
```


## Labels

`label`

```html
<span class="label label-default">Default</span>
```

`labeldefault`

```html
<span class="label label-default">Default</span>
```

`labelprimary`

```html
<span class="label label-primary">Primary</span>
```

`labelsuccess`

```html
<span class="label label-success">Success</span>
```

`labelinfo`

```html
<span class="label label-info">Info</span>
```

`labelwarning`

```html
<span class="label label-warning">Warning</span>
```

`labeldanger`

```html
<span class="label label-danger">Danger</span>
```


## Badges

`badge`

```html
<a href="#">Inbox <span class="badge">42</span></a>
```

`badgebtn`

```html
<button class="btn btn-primary" type="button">
  Messages <span class="badge">4</span>
</button>
```

`badgenav`

```html
<ul class="nav nav-pills" role="tablist">
  <li role="presentation" class="active"><a href="#">Home <span class="badge">42</span></a></li>
  <li role="presentation"><a href="#">Profile</a></li>
  <li role="presentation"><a href="#">Messages <span class="badge">3</span></a></li>
</ul>
```

## Jumbotron

`jumbotron`

```html
<div class="jumbotron">
  <h1>Hello, world!</h1>
  <p>...</p>
  <p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a></p>
</div>
```

`jumbotroncontainer`

```html
<div class="jumbotron">
  <div class="container">
    ...
  </div>
</div>
```


## Page header

`pageheader`

```html
<div class="page-header">
  <h1>Example page header <small>Subtext for header</small></h1>
</div>
```


## Thumbnails

`thumbnail`

```html
<a href="#" class="thumbnail">
  <img src="..." alt="...">
</a>
```

`thumbnailcontent`

```html
<div class="thumbnail">
  <img src="..." alt="...">
  <div class="caption">
    <h3>Thumbnail label</h3>
    <p>...</p>
    <p><a href="#" class="btn btn-primary" role="button">Button</a> <a href="#" class="btn btn-default" role="button">Button</a></p>
  </div>
</div>
```


## Alerts

`alert`

```html
<div class="alert alert-success" role="alert">...</div>
```

`alertsuccess`

```html
<div class="alert alert-success" role="alert">...</div>
```

`alertinfo`

```html
<div class="alert alert-info" role="alert">...</div>
```

`alertwarning`

```html
<div class="alert alert-warning" role="alert">...</div>
```

`alertdanger`

```html
<div class="alert alert-danger" role="alert">...</div>
```

`alertdismissible`

```html
<div class="alert alert-warning alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Warning!</strong> Better check yourself, you're not looking too good.
</div>
```

`alertlink`

```html
<div class="alert alert-success" role="alert">
  <a href="#" class="alert-link">...</a>
</div>
```


## Progress bars

`progress`

```html
<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
    <span class="sr-only">60% Complete</span>
  </div>
</div>
```

`progresssuccess`

```html
<div class="progress">
  <div class="progress-bar progress-bar-success" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
    <span class="sr-only">40% Complete (success)</span>
  </div>
</div>
```

`progressinfo`

```html
<div class="progress">
  <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100" style="width: 20%">
    <span class="sr-only">20% Complete</span>
  </div>
</div>
```

`progresswarning`

```html
<div class="progress">
  <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
    <span class="sr-only">60% Complete (warning)</span>
  </div>
</div>
```

`progressdanger`

```html
<div class="progress">
  <div class="progress-bar progress-bar-danger" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%">
    <span class="sr-only">80% Complete (danger)</span>
  </div>
</div>
```

`progressstriped`

```html
<div class="progress">
  <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%">
    <span class="sr-only">40% Complete (success)</span>
  </div>
</div>
```

`progressstripedactive`

```html
<div class="progress">
  <div class="progress-bar progress-bar-striped active" role="progressbar" aria-valuenow="45" aria-valuemin="0" aria-valuemax="100" style="width: 45%">
    <span class="sr-only">45% Complete</span>
  </div>
</div>
```

`progressstacked`

```html
<div class="progress">
  <div class="progress-bar progress-bar-success" style="width: 35%">
    <span class="sr-only">35% Complete (success)</span>
  </div>
  <div class="progress-bar progress-bar-warning progress-bar-striped" style="width: 20%">
    <span class="sr-only">20% Complete (warning)</span>
  </div>
  <div class="progress-bar progress-bar-danger" style="width: 10%">
    <span class="sr-only">10% Complete (danger)</span>
  </div>
</div>
```


## Media object

`media`

```html
<div class="media">
  <div class="media-left">
    <a href="#">
      <img class="media-object" src="..." alt="...">
    </a>
  </div>
  <div class="media-body">
    <h4 class="media-heading">Media heading</h4>
    ...
  </div>
</div>
```

`medialeft`

```html
<div class="media-left">
  <a href="#">
    <img class="media-object" src="..." alt="...">
  </a>
</div>
```

`mediabody`

```html
<div class="media-body">
  <h4 class="media-heading">Media heading</h4>
  ...
</div>
```

`mediaright`

```html
<div class="media-right">
  <a href="#">
    <img class="media-object" src="..." alt="...">
  </a>
</div>
```

`mediamiddle`

```html
<div class="media-left media-middle">
  <a href="#">
    <img class="media-object" src="..." alt="...">
  </a>
</div>
```

`mediabottom`

```html
<div class="media-left media-bottom">
  <a href="#">
    <img class="media-object" src="..." alt="...">
  </a>
</div>
```

`medialist`

```html
<ul class="media-list">
  <li class="media">
    <div class="media-left">
      <a href="#">
        <img class="media-object" src="..." alt="...">
      </a>
    </div>
    <div class="media-body">
      <h4 class="media-heading">Media heading</h4>
      ...
    </div>
  </li>
</ul>
```

## List group

`listgroup`

```html
<ul class="list-group">
  <li class="list-group-item">Cras justo odio</li>
  <li class="list-group-item">Dapibus ac facilisis in</li>
  <li class="list-group-item">Morbi leo risus</li>
  <li class="list-group-item">Porta ac consectetur ac</li>
  <li class="list-group-item">Vestibulum at eros</li>
</ul>
```

`listgroupitem`

```html
<li class="list-group-item">Cras justo odio</li>
```

`listgroupitembadge`

```html
<li class="list-group-item">
  <span class="badge">14</span>
  Cras justo odio
</li>
```

`alistgroupitem`

```html
<a href="#" class="list-group-item active">Cras justo odio</a>
```

`listgroupitemdisabled`

```html
<a href="#" class="list-group-item disabled">Cras justo odio</a>
```

`listgroupitemsuccess`

```html
<li class="list-group-item list-group-item-success">Dapibus ac facilisis in</li>
```

`listgroupiteminfo`

```html
<li class="list-group-item list-group-item-info">Cras sit amet nibh libero</li>
```

`listgroupitemwarning`

```html
<li class="list-group-item list-group-item-warning">Porta ac consectetur ac</li>
```

`listgroupitemdanger`

```html
<li class="list-group-item list-group-item-danger">Vestibulum at eros</li>
```

`alistgroupitemsuccess`

```html
<a href="#" class="list-group-item list-group-item-success">Dapibus ac facilisis in</a>
```

`alistgroupiteminfo`

```html
<a href="#" class="list-group-item list-group-item-info">Cras sit amet nibh libero</a>
```

`alistgroupitemwarning`

```html
<a href="#" class="list-group-item list-group-item-warning">Porta ac consectetur ac</a>
```

`alistgroupitemdanger`

```html
<a href="#" class="list-group-item list-group-item-danger">Vestibulum at eros</a>
```

`listgroupitemcontent`

```html
<li href="#" class="list-group-item">
  <h4 class="list-group-item-heading">List group item heading</h4>
  <p class="list-group-item-text">...</p>
</li>
```

`alistgroupitemcontent`

```html
<a href="#" class="list-group-item active">
  <h4 class="list-group-item-heading">List group item heading</h4>
  <p class="list-group-item-text">...</p>
</a>
```



## Panels

`panel`

```html
<div class="panel panel-default">
  <div class="panel-body">
    Basic panel example
  </div>
</div>
```

`panelheading`

```html
<div class="panel-heading">Panel heading without title</div>
```

`panelheadingtitle`

```html
<div class="panel-heading">
  <h3 class="panel-title">Panel title</h3>
</div>
```

`panelbody`

```html
<div class="panel-body">
  Panel content
</div>
```

`panelfooter`

```html
<div class="panel-footer">Panel footer</div>
```

`paneldefault`

```html
<div class="panel panel-default">
  <div class="panel-body">
    Basic panel example
  </div>
</div>
```

`panelprimary`

```html
<div class="panel panel-primary">...</div>
```

`panelsuccess`

```html
<div class="panel panel-success">...</div>
```

`panelinfo`

```html
<div class="panel panel-info">...</div>
```

`panelwarning`

```html
<div class="panel panel-warning">...</div>
```

`paneldanger`

```html
<div class="panel panel-danger">...</div>
```

`paneltable`

```html
<div class="panel panel-default">
  <!-- Default panel contents -->
  <div class="panel-heading">Panel heading</div>
  <div class="panel-body">
    <p>...</p>
  </div>

  <!-- Table -->
  <table class="table">
    ...
  </table>
</div>
```

`panellistgroup`

```html
<div class="panel panel-default">
  <!-- Default panel contents -->
  <div class="panel-heading">Panel heading</div>
  <div class="panel-body">
    <p>...</p>
  </div>

  <!-- List group -->
  <ul class="list-group">
    <li class="list-group-item">Cras justo odio</li>
    <li class="list-group-item">Dapibus ac facilisis in</li>
    <li class="list-group-item">Morbi leo risus</li>
    <li class="list-group-item">Porta ac consectetur ac</li>
    <li class="list-group-item">Vestibulum at eros</li>
  </ul>
</div>
```


## Responsive embed

`embedresponsive`

```html
<!-- 16:9 aspect ratio -->
<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="..."></iframe>
</div>

<!-- 4:3 aspect ratio -->
<div class="embed-responsive embed-responsive-4by3">
  <iframe class="embed-responsive-item" src="..."></iframe>
</div>
```


## Wells

`well`

```html
<div class="well">...</div>
```

`welllg`

```html
<div class="well well-lg">...</div>
```

`wellsm`

```html
<div class="well well-sm">...</div>
```


# Javascript

## Modal

`modal`

```html
<div class="modal fade">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title">Modal title</h4>
      </div>
      <div class="modal-body">
        <p>One fine body&hellip;</p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div><!-- /.modal-content -->
  </div><!-- /.modal-dialog -->
</div><!-- /.modal -->
```

`modallg`

```html
<div class="modal fade bs-example-modal-lg" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">
      ...
    </div>
  </div>
</div>
```

`modalsm`

```html
<div class="modal fade bs-example-modal-sm" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-sm">
    <div class="modal-content">
      ...
    </div>
  </div>
</div>
```


## Scrollspy

`scrollspy`

```html
<body data-spy="scroll" data-target=".navbar-example">
  ...
  <div class="navbar-example">
    <ul class="nav nav-tabs" role="tablist">
      ...
    </ul>
  </div>
  ...
</body>
```

## Tab

`tabpanel`

```html
<div role="tabpanel">

  <!-- Nav tabs -->
  <ul class="nav nav-tabs" role="tablist">
    <li role="presentation" class="active"><a href="#home" aria-controls="home" role="tab" data-toggle="tab">Home</a></li>
    <li role="presentation"><a href="#profile" aria-controls="profile" role="tab" data-toggle="tab">Profile</a></li>
    <li role="presentation"><a href="#messages" aria-controls="messages" role="tab" data-toggle="tab">Messages</a></li>
    <li role="presentation"><a href="#settings" aria-controls="settings" role="tab" data-toggle="tab">Settings</a></li>
  </ul>

  <!-- Tab panes -->
  <div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="home">...</div>
    <div role="tabpanel" class="tab-pane" id="profile">...</div>
    <div role="tabpanel" class="tab-pane" id="messages">...</div>
    <div role="tabpanel" class="tab-pane" id="settings">...</div>
  </div>

</div>
```

## Tooltip

`tooltip`

```html
<button type="button" class="btn btn-default" data-toggle="tooltip" title="Tooltip on left">Tooltip on left</button>
```

`atooltip`

```html
<a href="#" data-toggle="tooltip" title="Tooltip on left">Tooltip on left</a>
```

`tooltiptop`

```html
<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="top" title="Tooltip on top">Tooltip on top</button>
```

`atooltiptop`

```html
<a href="#" data-toggle="tooltip" data-placement="top" title="Tooltip on top">Tooltip on top</a>
```

`tooltipleft`

```html
<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="left" title="Tooltip on left">Tooltip on left</button>
```

`atooltipleft`

```html
<a href="#" data-toggle="tooltip" data-placement="left" title="Tooltip on left">Tooltip on left</a>
```

`tooltipbottom`

```html
<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom">Tooltip on bottom</button>
```

`atooltipbottom`

```html
<a href="#" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom">Tooltip on bottom</a>
```

`tooltipright`

```html
<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="right" title="Tooltip on right">Tooltip on right</button>
```

`atooltipright`

```html
<a href="#" data-toggle="tooltip" data-placement="right" title="Tooltip on right">Tooltip on right</a>
```


## Popover

`popover`

```html
<button type="button" class="btn btn-default" data-toggle="popover" title="Popover title" data-content="And here's some amazing content. It's very engaging. Right?">Click to toggle popover</button>
```

`apopover`

```html
<a class="btn btn-default" role="button" data-toggle="popover" title="Dismissible popover" data-content="And here's some amazing content. It's very engaging. Right?">Dismissible popover</a>
```

`popovertop`

```html
<button type="button" class="btn btn-default" data-container="body" data-toggle="popover" data-placement="top" data-content="Vivamus sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on top
</button>
```

`apopovertop`

```html
<a class="btn btn-default" role="button" data-toggle="popover" data-placement="top" title="Popover on top" data-content="And here's some amazing content. It's very engaging. Right?">Popover on top</a>
```

`popoverleft`

```html
<button type="button" class="btn btn-default" data-container="body" data-toggle="popover" data-placement="left" data-content="Vivamus sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on left
</button>
```

`apopoverleft`

```html
<a class="btn btn-default" role="button" data-toggle="popover" data-placement="left" title="Popover on left" data-content="And here's some amazing content. It's very engaging. Right?">Popover on left</a>
```

`popoverbottom`

```html
<button type="button" class="btn btn-default" data-container="body" data-toggle="popover" data-placement="bottom" data-content="Vivamus
sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on bottom
</button>
```

`apopoverbottom`

```html
<a class="btn btn-default" role="button" data-toggle="popover" data-placement="bottom" title="Popover on bottom" data-content="And here's some amazing content. It's very engaging. Right?">Popover on bottom</a>
```

`popoverright`

```html
<button type="button" class="btn btn-default" data-container="body" data-toggle="popover" data-placement="right" data-content="Vivamus sagittis lacus vel augue laoreet rutrum faucibus.">
  Popover on right
</button>
```

`apopoverright`

```html
<a class="btn btn-default" role="button" data-toggle="popover" data-placement="right" title="Popover on right" data-content="Vivamus sagittis lacus vel augue laoreet rutrum faucibus.">Popover on right</a>
```

`apopoverdismissible`

```html
<a tabindex="0" class="btn btn-default" role="button" data-toggle="popover" data-trigger="focus" title="Dismissible popover" data-content="And here's some amazing content. It's very engaging. Right?">Dismissible popover</a>
```


## Button

`btnstatetext`

```html
<button type="button" id="myButton" data-loading-text="Loading..." class="btn btn-default" autocomplete="off">
  Loading state
</button>
```

`btnsingletoggle`

```html
<button type="button" class="btn btn-default" data-toggle="button" aria-pressed="false" autocomplete="off">
  Single toggle
</button>
```

`btngroupcheckbox`

```html
<div class="btn-group" data-toggle="buttons">
  <label class="btn btn-primary active">
    <input type="checkbox" autocomplete="off" checked> Checkbox 1 (pre-checked)
  </label>
  <label class="btn btn-primary">
    <input type="checkbox" autocomplete="off"> Checkbox 2
  </label>
  <label class="btn btn-primary">
    <input type="checkbox" autocomplete="off"> Checkbox 3
  </label>
</div>
```

`btngroupradio`

```html
<div class="btn-group" data-toggle="buttons">
  <label class="btn btn-primary active">
    <input type="radio" name="options" id="option1" autocomplete="off" checked> Radio 1 (preselected)
  </label>
  <label class="btn btn-primary">
    <input type="radio" name="options" id="option2" autocomplete="off"> Radio 2
  </label>
  <label class="btn btn-primary">
    <input type="radio" name="options" id="option3" autocomplete="off"> Radio 3
  </label>
</div>
```


## Collapse

`btncollapse`

```html
<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
  Button with data-target
</button>
<div class="collapse" id="collapseExample">
  <div class="well">
    ...
  </div>
</div>
```

`abtncollapse`

```html
<a class="btn btn-primary" data-toggle="collapse" href="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
  Link with href
</a>
<div class="collapse" id="collapseExample">
  <div class="well">
    ...
  </div>
</div>
```

`accordian`

```html
<div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingOne">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          Collapsible Group Item #1
        </a>
      </h4>
    </div>
    <div id="collapseOne" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          Collapsible Group Item #2
        </a>
      </h4>
    </div>
    <div id="collapseTwo" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Collapsible Group Item #3
        </a>
      </h4>
    </div>
    <div id="collapseThree" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
      </div>
    </div>
  </div>
</div>
```


## Carousel

`carousel`

```html
<div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ol class="carousel-indicators">
    <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
    <li data-target="#carousel-example-generic" data-slide-to="1"></li>
    <li data-target="#carousel-example-generic" data-slide-to="2"></li>
  </ol>

  <!-- Wrapper for slides -->
  <div class="carousel-inner" role="listbox">
    <div class="item active">
      <img src="..." alt="...">
      <div class="carousel-caption">
        ...
      </div>
    </div>
    <div class="item">
      <img src="..." alt="...">
      <div class="carousel-caption">
        ...
      </div>
    </div>
    ...
  </div>

  <!-- Controls -->
  <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
```


## Affix

`affix`

```html
<div data-spy="affix" data-offset-top="60" data-offset-bottom="200">
  ...
</div>
```


