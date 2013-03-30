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



Base CSS: Typography
====================

Lead body copy
--------------

`lead`

    <p class="lead">${1:...}</p>

Alignment classes
-----------------

`textleft`

    <p class="text-left">${1:Left aligned text.}</p>

`textcenter`

    <p class="text-center">${1:Center aligned text.}</p>

`textright`

    <p class="text-right">${1:Right aligned text.}</p>

Emphasis classes
----------------

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
-------------

`initialism`

    <abbr title="${1:HyperText Markup Language}" class="initialism">${2:HTML}</abbr>

Lists: Unstyled
---------------

`unstyled`

    <ul class="unstyled">
      <li>${1:...}</li>
    </ul>

Lists: Inline
-------------

`inline`

    <ul class="inline">
      <li>...</li>
    </ul>

Description: Horizontal description
-----------------------------------

`dlhorizontal`

    <dl class="dl-horizontal">
      <dt>${1:...}</dt>
      <dd>${2:...}</dd>
    </dl>

Base CSS: Tables
==============

Default styles
--------------

`table`

    <table class="table">
      ${1:...}
    </table>

Optional classes
----------------

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


Base CSS: Code
===============

`prescrollable`

    <pre class="pre-scrollable">
      ${1:&lt;p&gt;Sample text here...&lt;/p&gt;}
    </pre>


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
-----------------------------

`formsearch`

    <form class="form-search">
      <input type="text" class="input-medium search-query">
      <button type="submit" class="btn">${1:Search}</button>
    </form>

Optional layouts: Inline form
-----------------------------

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
---------------------------------

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

    <label class="checkbox inline">
      <input type="checkbox" id="${1:inlineCheckbox1}" value="${2:option1}"> ${3:1}
    </label>


Prepended and appended inputs
-----------------------------

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

    <div class="input-prepend input-append">
      <span class="add-on">${1:$}</span>
      <input class="span2" id="${2:appendedPrependedInput}" type="text">
      <span class="add-on">${3:.00}</span>
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
--------------

`inputblocklevel`

    <input class="input-block-level" type="text">

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

    <span class="input-large uneditable-input">${1:Some value here}</span>

Form actions
------------

`formactions`

    <div class="form-actions">
      <button type="submit" class="btn btn-primary">${1:Save changes}</button>
      <button type="button" class="btn">${2:Cancel}</button>
    </div>

Help text: Inline help
----------------------

`helpblock`

    <span class="help-block">${1:A longer block of help text that breaks onto a new line and may extend beyond one line.}</span>


Help text: Block help
---------------------

`helpinline`

    <span class="help-inline">${1:Inline help text}</span>


Base CSS: Buttons
=================

`btn`

    <button type="button" class="btn">${2:Default}</button>

`abtn`

    <a href="${1:#}" class="btn">${2:Text}</a>

`btnprimary`

    <button type="button" class="btn btn-primary">${1:Default}</button>

`abtnprimary`

    <a href="${1:#}" class="btn btn-primary">${2:Text}</a>

`btninfo`

    <button type="button" class="btn btn-info">${1:Default}</button>

`abtninfo`

    <a href="${1:#}" class="btn btn-info">${2:Text}</a>

`btnsuccess`

    <button type="button" class="btn btn-success">${1:Default}</button>

`abtnsuccess`

    <a href="${1:#}" class="btn btn-success">${2:Text}</a>

`btnwarning`

    <button type="button" class="btn btn-warning">${1:Default}</button>

`abtnwarning`

    <a href="${1:#}" class="btn btn-warning">${2:Text}</a>

`btndanger`

    <button type="button" class="btn btn-danger">${1:Default}</button>

`abtndanger`

    <a href="${1:#}" class="btn btn-danger">${2:Text}</a>

`btninverse`

    <button type="button" class="btn btn-inverse">${1:Default}</button>

`abtninverse`

    <a href="${1:#}" class="btn btn-inverse">${2:Text}</a>

`btnlink`

    <button type="button" class="btn btn-link">${1:Default}</button>

`btnlarge`

    <button type="button" class="btn btn-large">${1:Default}</button>

`abtnlarge`

    <a href="${1:#}" class="btn btn-large">${2:Text}</a>

`btnsmall`

    <button type="button" class="btn btn-small">${1:Default}</button>

`abtnsmall`

    <a href="${1:#}" class="btn btn-small">${2:Text}</a>

`btnmini`

    <button type="button" class="btn btn-mini">${1:Default}</button>

`abtnmini`

    <a href="${1:#}" class="btn btn-mini">${2:Text}</a>

`btnblock`

    <button class="btn btn-large btn-block" type="button">${1:Block level button}</button>

`abtnblock`

    <a href="${1:#}" class="btn btn-block">${2:Text}</a>


Disabled state
--------------

`adisabled`

    <a href="#" class="btn disabled">${1:Primary link}</a>

`btndisabled`

    <button type="button" class="btn disabled" disabled="disabled">${1:Primary button}</button>



Base CSS: Images
================

`imgrounded`

    <img src="${1:...}" class="img-rounded">

`imgcircle`

    <img src="${1:...}" class="img-circle">

`imgpolaroid`

    <img src="${1:...}" class="img-polaroid">


Base CSS: Icons
===============

`icon`

    <i class="icon-${1:search}"></i>

`iconwhite`

    <i class="icon-${1:search} icon-white"></i>


Components: Dropdowns
=====================

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


Components: Button groups
=====================

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


Components: Button dropdowns
=====================

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

`btndropup`

    <div class="btn-group dropup">
      <button class="btn">${1:Dropup}</button>
      <button class="btn dropdown-toggle" data-toggle="dropdown">
        <span class="caret"></span>
      </button>
      <ul class="dropdown-menu">
        ${2:<!-- dropdown menu links -->}
      </ul>
    </div>


Components: Navs
=====================

`navtabs`

    <ul class="nav nav-tabs">
      <li class="active">
        <a href="#">${1:Home}</a>
      </li>
      <li><a href="#">${2:...}</a></li>
      <li><a href="#">${3:...}</a></li>
    </ul>

`navpills`

    <ul class="nav nav-pills">
      <li class="active">
        <a href="#">${1:Home}</a>
      </li>
      <li><a href="#">${2:...}</a></li>
      <li><a href="#">${3:...}</a></li>
    </ul>

`navtabsstacked`

    <ul class="nav nav-tabs nav-stacked">
      ${1:...}
    </ul>

`navpillsstacked`

    <ul class="nav nav-pills nav-stacked">
      ${1:...}
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

`navlist`

    <ul class="nav nav-list">
      <li class="nav-header">${1:List header}</li>
      <li class="active"><a href="#">${2:Home}</a></li>
      <li><a href="#">${3:Library}</a></li>
      <li class="divider"></li>
      ${4:...}
    </ul>

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

`tabbabletabsbelow`

    <div class="tabbable tabs-below">
      <div class="tab-content">
        ${1:...}
      </div>
      <ul class="nav nav-tabs">
        ${2:...}
      </ul>
    </div>

`tabbabletabsleft`

    <div class="tabbable tabs-left">
      <ul class="nav nav-tabs">
        ${1:...}
      </ul>
      <div class="tab-content">
        ${2:...}
      </div>
    </div>

`tabbabletabsright`

    <div class="tabbable tabs-right">
      <ul class="nav nav-tabs">
        ${1:...}
      </ul>
      <div class="tab-content">
        ${2:...}
      </div>
    </div>


Components: Navbar
=====================

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

`navbarform`

    <form class="navbar-form pull-left">
      <input type="text" class="span2">
      <button type="submit" class="btn">${1:Submit}</button>
    </form>

`navbarsearch`

    <form class="navbar-search pull-left">
      <input type="text" class="search-query" placeholder="${1:Search}">
    </form>

`navbarfixedtop`

    <div class="navbar navbar-fixed-top">
      ${1:...}
    </div>

`navbarfixedbottom`

    <div class="navbar navbar-fixed-bottom">
      ${1:...}
    </div>

`navbarstatictop`

    <div class="navbar navbar-static-top">
      ${1:...}
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


`navbarinverse`

    <div class="navbar navbar-inverse">
      ...
    </div>




TODO Components: Breadcrumbs
=====================

`breadcrumb`

    <ul class="breadcrumb">
      <li><a href="#">Home</a> <span class="divider">/</span></li>
      <li><a href="#">Library</a> <span class="divider">/</span></li>
      <li class="active">Data</li>
    </ul>

TODO Components: Pagination
=====================

`pagination`

    <div class="pagination">
      <ul>
        <li><a href="#">Prev</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">2</a></li>
        <li><a href="#">3</a></li>
        <li><a href="#">4</a></li>
        <li><a href="#">5</a></li>
        <li><a href="#">Next</a></li>
      </ul>
    </div>

`pagination-large`

    <div class="pagination pagination-large">
      <ul>
        ...
      </ul>
    </div>

`pagination-small`

    <div class="pagination pagination-small">
      <ul>
        ...
      </ul>
    </div>

`pagination-mini`

    <div class="pagination pagination-mini">
      <ul>
        ...
      </ul>
    </div>

`pagination-centered`

    <div class="pagination pagination-centered">
      ...
    </div>

`pagination-right`

    <div class="pagination pagination-right">
      ...
    </div>

`pager`

    <ul class="pager">
      <li><a href="#">Previous</a></li>
      <li><a href="#">Next</a></li>
    </ul>

`pageraligned`

    <ul class="pager">
      <li class="previous">
        <a href="#">&larr; Older</a>
      </li>
      <li class="next">
        <a href="#">Newer &rarr;</a>
      </li>
    </ul>


TODO Components: Labels and badges
=====================

`label`

    <span class="label">Default</span>

`labelsuccess`

    <span class="label label-success">Success</span>

`labelwarning`

    <span class="label label-warning">Warning</span>

`labelimportant`

    <span class="label label-important">Important</span>

`labelinfo`

    <span class="label label-info">Info</span>

`labelinverse`

    <span class="label label-inverse">Inverse</span>

`badge`

    <span class="badge">1</span>

`badgesuccess`

    <span class="badge badge-success">2</span>

`badgewarning`

    <span class="badge badge-warning">4</span>

`badgeimportant`

    <span class="badge badge-important">6</span>

`badgeinfo`

    <span class="badge badge-info">8</span>

`badgeinverse`

    <span class="badge badge-inverse">10</span>


TODO Components: Typography
=====================

`herounit`

    <div class="hero-unit">
      <h1>Heading</h1>
      <p>Tagline</p>
      <p>
        <a class="btn btn-primary btn-large">
          Learn more
        </a>
      </p>
    </div>

`pageheader`

    <div class="page-header">
      <h1>Example page header <small>Subtext for header</small></h1>
    </div>


TODO Components: Thumbnails
=====================

`thumbnails`

    <ul class="thumbnails">
      <li class="span4">
        <a href="#" class="thumbnail">
          <img data-src="holder.js/300x200" alt="">
        </a>
      </li>
      ...
    </ul>

`thumbnailsdiv`

    <ul class="thumbnails">
      <li class="span4">
        <div class="thumbnail">
          <img data-src="holder.js/300x200" alt="">
          <h3>Thumbnail label</h3>
          <p>Thumbnail caption...</p>
        </div>
      </li>
      ...
    </ul>




TODO Components: Alerts
=====================

`alert`

    <div class="alert">
      <button type="button" class="close" data-dismiss="alert">&times;</button>
      <strong>Warning!</strong> Best check yo self, you're not looking too good.
    </div>

`alertblock`

    <div class="alert alert-block">
      <button type="button" class="close" data-dismiss="alert">&times;</button>
      <h4>Warning!</h4>
      Best check yo self, you're not...
    </div>

`alerterror`

    <div class="alert alert-error">
      ...
    </div>

`alertsuccess`

    <div class="alert alert-success">
      ...
    </div>

`alertinfo`

    <div class="alert alert-info">
      ...
    </div>


TODO Components: Progress bar
=====================

`progress`

    <div class="progress">
      <div class="bar" style="width: 60%;"></div>
    </div>

`progressstriped`

    <div class="progress progress-striped">
      <div class="bar" style="width: 20%;"></div>
    </div>

`progressstripedactive`

    <div class="progress progress-striped active">
      <div class="bar" style="width: 40%;"></div>
    </div>

`progressstacked`

    <div class="progress">
      <div class="bar bar-success" style="width: 35%;"></div>
      <div class="bar bar-warning" style="width: 20%;"></div>
      <div class="bar bar-danger" style="width: 10%;"></div>
    </div>

`progressinfo`

    <div class="progress progress-info">
      <div class="bar" style="width: 20%"></div>
    </div>

`progresssuccess`

    <div class="progress progress-success">
      <div class="bar" style="width: 40%"></div>
    </div>

`progresswarning`

    <div class="progress progress-warning">
      <div class="bar" style="width: 60%"></div>
    </div>

`progressdanger`

    <div class="progress progress-danger">
      <div class="bar" style="width: 80%"></div>
    </div>



TODO Components: Media object
=====================

`media`

    <div class="media">
      <a class="pull-left" href="#">
        <img class="media-object" data-src="holder.js/64x64">
      </a>
      <div class="media-body">
        <h4 class="media-heading">Media heading</h4>
        ...

        <!-- Nested media object -->
        <div class="media">
          ...
        </div>
      </div>
    </div>

`medialist`

    <ul class="media-list">
      <li class="media">
        <a class="pull-left" href="#">
          <img class="media-object" data-src="holder.js/64x64">
        </a>
        <div class="media-body">
          <h4 class="media-heading">Media heading</h4>
          ...

          <!-- Nested media object -->
          <div class="media">
            ...
         </div>
        </div>
      </li>
    </ul>

TODO Components: Misc
=====================

`well`

    <div class="well">
      ...
    </div>

`welllarge`

    <div class="well well-large">
      ...
    </div>

`wellsmall`

    <div class="well well-small">
      ...
    </div>

`close`

    <button class="close">&times;</button>

`aclose`

    <a class="close" href="#">&times;</a>

