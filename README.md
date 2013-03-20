Twitter Bootstrap Snippets for snipmate.vim
===========================================

HTML and Haml snippets of Twitter Bootstrap scaffolding, base css and components.

Generally the snippet trigger will be the name of the class.


Scaffolding
===========

Basic grid HTML
---------------

`row`

    <div class="row">
      <div class="span${1:4}">${2:...}</div>
      <div class="span${3:8}">${4:...}</div>
    </div>

Basic fluid grid HTML
---------------------

`rowfluid`

    <div class="row-fluid">
      <div class="span${1:4}">${2:...}</div>
      <div class="span${3:8}">${4:...}</div>
    </div>

Fixed Container
---------------

`container`

    <div class="container">
      ${1:...}
    </div>

Fluid Container
---------------

`containerfluid`

    <div class="container-fluid">
      ${1:...}
    </div>



Base CSS
========

Base CSS: Typography
====================

Lead body copy

`lead`

    <p class="lead">${1:...}</p>

Alignment classes

    TODO

Emphasis classes

`muted`

    <p class="muted">${1:Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.}</p>

`textwarning`

    <p class="text-warning">${1:Etiam porta sem malesuada magna mollis euismod.}</p>

`texterror`

    <p class="text-error">${1:Donec ullamcorper nulla non metus auctor fringilla.}</p>

`textinfo`

    <p class="text-info">${1:Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis.}</p>

`textsuccess`

    <p class="text-success">${1:Duis mollis, est non commodo luctus, nisi erat porttitor ligula.}</p>

Abbreviations

`initialism`

    <abbr title="${1:HyperText Markup Language}" class="initialism">${2:HTML}</abbr>

Lists: Unstyled

`unstyled`

    <ul class="unstyled">
      <li>${1:...}</li>
    </ul>

Lists: Unstyled

    TODO
    <ul class="inline">
      <li>...</li>
    </ul>

Description: Horizontal description

`dlhorizontal`

    <dl class="dl-horizontal">
      <dt>${1:...}</dt>
      <dd>${2:...}</dd>
    </dl>

Base CSS: Tables
==============

Default styles

`table`

    <table class="table">
      ${1:...}
    </table>

Optional classes

`tablestriped`

    <table class="table table-striped">
      ${1:...}
    </table>

`tablebordered`

    <table class="table table-bordered">
      ${1:...}
    </table>

`tablehover`

    <table class="table table-hover">
      ${1:...}
    </table>

`tablecondensed`

    <table class="table table-condensed">
      ${1:...}
    </table>


Base CSS: Forms
===============

Default Styles
--------------

`form`

    <form>
      <fieldset>
        <legend>${1:Legend}</legend>
        <label>${2:Label name}</label>
        <input type="text" placeholder="${3:Type something…}">
        <span class="help-block">${4:Example block-level help text here.}</span>
        <label class="checkbox">
          <input type="checkbox"> ${5:Check me out}
        </label>
        <button type="submit" class="btn">${6:Submit}</button>
      </fieldset>
    </form>

Optional layouts: Search form

`formsearch`

    <form class="form-search">
      <input type="text" class="input-medium search-query">
      <button type="submit" class="btn">${1:Search}</button>
    </form>

Optional layouts: Inline form

`forminline`

    <form class="form-inline">
      <input type="text" class="input-small" placeholder="${1:Email}">
      <input type="password" class="input-small" placeholder="${2:Password}">
      <label class="checkbox">
        <input type="checkbox"> ${3:Remember me}
      </label>
      <button type="submit" class="btn">${4:Sign in}</button>
    </form>

Optional layouts: Horizontal form

`formhorizontal`

    <form class="form-horizontal">
      <div class="control-group">
        <label class="control-label" for="inputEmail">Email</label>
        <div class="controls">
          <input type="text" id="inputEmail" placeholder="Email">
        </div>
      </div>
      <div class="control-group">
        <label class="control-label" for="inputPassword">Password</label>
        <div class="controls">
          <input type="password" id="inputPassword" placeholder="Password">
        </div>
      </div>
      <div class="control-group">
        <div class="controls">
          <label class="checkbox">
            <input type="checkbox"> Remember me
          </label>
          <button type="submit" class="btn">Sign in</button>
        </div>
      </div>
    </form>

`checkboxinline`

    TODO
    <label class="checkbox inline">
      <input type="checkbox" id="inlineCheckbox1" value="option1"> 1
    </label>
    <label class="checkbox inline">
      <input type="checkbox" id="inlineCheckbox2" value="option2"> 2
    </label>
    <label class="checkbox inline">
      <input type="checkbox" id="inlineCheckbox3" value="option3"> 3
    </label>

Extending form controls

Prepended and appended inputs

`inputappend`

    <div class="input-append">
      <input class="span2" id="appendedInput" type="text">
      <span class="add-on">${1:.00}</span>
    </div>

`inputprepend`

    <div class="input-prepend">
      <span class="add-on">${1:@}</span>
      <input class="span2" id="prependedInput" type="text" placeholder="${2:Username}">
    </div>

`inputprependappend`

    TODO
    <div class="input-prepend input-append">
      <span class="add-on">$</span>
      <input class="span2" id="appendedPrependedInput" type="text">
      <span class="add-on">.00</span>
    </div>

`inputappendbtn`

    <div class="input-append">
      <input class="span2" id="appendedInputButton" type="text">
      <button class="btn" type="button">${1:Go!}</button>
    </div>

`inputappendbtndropdown`

    <div class="input-append">
      <input class="span2" id="appendedDropdownButton" type="text">
      <div class="btn-group">
        <button class="btn dropdown-toggle" data-toggle="dropdown">
          ${1:Action}
          <span class="caret"></span>
        </button>
        <ul class="dropdown-menu">
          ${2:...}
        </ul>
      </div>
    </div>

Control sizing

`inputblocklevel`

    TODO
    <input class="input-block-level" type="text" placeholder=".input-block-level">


`inputmini`

<input class="input-mini" type="text">

`inputsmall`

<input class="input-small" type="text">

`inputmedium`

<input class="input-medium" type="text">

`inputlarge`

<input class="input-large" type="text">

`inputxlarge`

<input class="input-xlarge" type="text">

`inputxxlarge`

<input class="input-xxlarge" type="text">



`controlsrow`

    <div class="controls controls-row">
      <input class="${1:span4}" type="text" placeholder="${2:.span4}">
      <input class="${3:span1}" type="text" placeholder="${4:.span1}">
    </div>

`uneditableinput`

    TODO
    <span class="input-xlarge uneditable-input">Some value here</span>

Form actions

`formactions`

    <div class="form-actions">
      <button type="submit" class="btn btn-primary">${1:Save changes}</button>
      <button type="button" class="btn">${2:Cancel}</button>
    </div>

Help text: Inline help

`helpblock`

    <span class="help-block">${1:A longer block of help text that breaks onto a new line and may extend beyond one line.}</span>


Help text: Block help

`helpinline`

    <span class="help-inline">${1:Inline help text}</span>


Base CSS: Buttons
=================

`btn`

    TODO
    <button type="button" class="btn">${2:Default}</button>

`abtn`

    <a href="${1:#}" class="btn btn-${2:primary}">${3:Text}</a>

`btnprimary`

    <button type="button" class="btn btn-primary">${1:Default}</button>

`btninfo`

    <button type="button" class="btn btn-info">${1:Default}</button>

`btnsuccess`

    <button type="button" class="btn btn-success">${1:Default}</button>

`btnwarning`

    <button type="button" class="btn btn-warning">${1:Default}</button>

`btndanger`

    <button type="button" class="btn btn-danger">${1:Default}</button>

`btninverse`

    <button type="button" class="btn btn-inverse">${1:Default}</button>

`btnlink`

    <button type="button" class="btn btn-link">${1:Default}</button>

`btnlarge`

    <button type="button" class="btn btn-large">${1:Default}</button>

`btnsmall`

    <button type="button" class="btn btn-small">${1:Default}</button>

`btnmini`

    <button type="button" class="btn btn-mini">${1:Default}</button>

`btnblock`

    <button class="btn btn-large btn-block btn-${1:primary}" type="button">${2:Block level button}</button>


Disabled state

`adisabled`

<a href="#" class="btn disabled">Primary link</a>

`btndisabled`

<button type="button" class="btn disabled" disabled="disabled">Primary button</button>



Base CSS: Images
----------------

TODO

`imgrounded`

    <img src="..." class="img-rounded">

`imgcircle`

    <img src="..." class="img-circle">

`imgpolaroid`

    <img src="..." class="img-polaroid">

Base CSS: Icons
---------------

`icon`

    <i class="icon-${1:search}"></i>

`iconwhite`

    <i class="icon-${1:search} icon-white"></i>


Other
-----



`btndropdown`

    <div class="btn-group">
      <a class="btn dropdown-toggle" data-toggle="dropdown" href="#">
        ${1:Action}
        <span class="caret"></span>
      </a>
      <ul class="dropdown-menu">
        ${2:<!-- dropdown menu links -->}
      </ul>
    </div>

`btndropdownsplit`

    <div class="btn-group">
      <button class="btn">${1:Action}</button>
      <button class="btn dropdown-toggle" data-toggle="dropdown">
        <span class="caret"></span>
      </button>
      <ul class="dropdown-menu">
        ${2:<!-- dropdown menu links -->}
      </ul>
    </div>

`btngroup`

    <div class="btn-group">
      <button class="btn">${1:1}</button>
      <button class="btn">${2:2}</button>
      <button class="btn">${3:3}</button>
    </div>

`btngroupvertical`

    <div class="btn-group btn-group-vertical">
      ${1:...}
    </div>

`btntoolbar`

    <div class="btn-toolbar">
      <div class="btn-group">
        ${1:...}
      </div>
    </div>

`dropdownmenu`

    <div class="dropdown">
      <!-- Link or button to toggle dropdown -->
      <ul class="dropdown-menu" role="menu" aria-labelledby="dLabel">
        <li><a tabindex="-1" href="#">${1:Action}</a></li>
        <li><a tabindex="-1" href="#">${2:Another action}</a></li>
        <li><a tabindex="-1" href="#">${3:Something else here}</a></li>
        <li class="divider"></li>
        <li><a tabindex="-1" href="#">${4:Separated link}</a></li>
      </ul>
    </div>


`navbar`

    <div class="navbar">
      <div class="navbar-inner">
        <a class="brand" href="#">${1:Title}</a>
        <ul class="nav">
          <li class="active"><a href="#">${2:Home}</a></li>
          <li><a href="#">${3:Link}</a></li>
          <li><a href="#">${4:Link}</a></li>
        </ul>
      </div>
    </div>

`navbarcollapse`

    <div class="navbar">
      <div class="navbar-inner">
        <div class="container">
     
          <!-- .btn-navbar is used as the toggle for collapsed navbar content -->
          <a class="btn btn-navbar" data-toggle="collapse" data-target=".nav-collapse">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </a>
     
          <!-- Be sure to leave the brand out there if you want it shown -->
          <a class="brand" href="#">${1:Project name}</a>
     
          <!-- Everything you want hidden at 940px or less, place within here -->
          <div class="nav-collapse collapse">
            ${2:<!-- .nav, .navbar-search, .navbar-form, etc -->}
          </div>
     
        </div>
      </div>
    </div>

`navbarfixedtop`

    <div class="navbar navbar-fixed-top">
      ${1:...}
    </div>

`navbarform`

    <form class="navbar-form pull-left">
      <input type="text" class="span2">
      <button type="submit" class="btn">${1:Submit}</button>
    </form>

`navbarsearch`

    <form class="navbar-search pull-left">
      <input type="text" class="search-query" placeholder="${1:Search}">
    </form>

`navbarstatictop`

    <div class="navbar navbar-static-top">
      ${1:...}
    </div>

`navlist`

    <ul class="nav nav-list">
      <li class="nav-header">${1:List header}</li>
      <li class="active"><a href="#">${2:Home}</a></li>
      <li><a href="#">${3:Library}</a></li>
      <li class="divider"></li>
      ${4:...}
    </ul>

`navpills`

    <ul class="nav nav-pills">
      <li class="active">
        <a href="#">${1:Home}</a>
      </li>
      <li><a href="#">${2:...}</a></li>
      <li><a href="#">${3:...}</a></li>
    </ul>

`navpillsdropdown`

    <ul class="nav nav-pills">
      <li class="dropdown">
        <a class="dropdown-toggle" data-toggle="dropdown" href="#">
            ${1:Dropdown}
            <b class="caret"></b>
          </a>
        <ul class="dropdown-menu">
          ${2:<!-- links -->}
        </ul>
      </li>
    </ul>

`navpillsstacked`

    <ul class="nav nav-pills nav-stacked">
      ${1:...}
    </ul>

`navtabs`

    <ul class="nav nav-tabs">
      <li class="active">
        <a href="#">${1:Home}</a>
      </li>
      <li><a href="#">${2:...}</a></li>
      <li><a href="#">${3:...}</a></li>
    </ul>

`navtabsdropdown`

    <ul class="nav nav-tabs">
      <li class="dropdown">
        <a class="dropdown-toggle" data-toggle="dropdown" href="#">
          ${1:Dropdown}
          <b class="caret"></b>
        </a>
        <ul class="dropdown-menu">
          ${2:<!-- links -->}
        </ul>
      </li>
    </ul>

`navtabsstacked`

    <ul class="nav nav-tabs nav-stacked">
      ${1:...}
    </ul>

`prescrollable`

    <pre class="pre-scrollable">
      ${1:&lt;p&gt;Sample text here...&lt;/p&gt;}
    </pre>

`tabbable`

    <div class="tabbable"> <!-- Only required for left/right tabs -->
      <ul class="nav nav-tabs">
        <li class="active"><a href="#tab1" data-toggle="tab">${1:Section 1}</a></li>
        <li><a href="#tab2" data-toggle="tab">${2:Section 2}</a></li>
      </ul>
      <div class="tab-content">
        <div class="tab-pane active" id="tab1">
          <p>${3:I'm in Section 1.}</p>
        </div>
        <div class="tab-pane" id="tab2">
          <p>${4:Howdy, I'm in Section 2.}</p>
        </div>
      </div>
    </div>

