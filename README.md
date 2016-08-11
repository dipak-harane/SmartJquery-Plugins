<div class="container-fluid">

<div class="container-content">

<div id="messageboxes">

<div id="lobibox-messagebox-examples">

### Examples

<div>

<div class="bs-example">

<fieldset>

<div class="bs-example"><button id="popupYesNoBasic" class="btn btn-primary">Confirm</button></div>

</fieldset>

<fieldset>

<div class="bs-example"><button id="popupErrorBasic" class="btn btn-danger">Show Error</button> <button id="popupSuccessBasic" class="btn btn-success">Show Success</button> <button id="popupInfoBasic" class="btn btn-info">Show info</button> <button id="popupWarningBasic" class="btn btn-warning">Show Warning</button></div>

</fieldset>

<fieldset>

<div class="bs-example"><button id="popupPromptBasic" class="btn btn-primary">Prompt</button></div>

</fieldset>

<fieldset>

<div class="bs-example"><button id="popupProgressBasic" class="btn btn-primary">Progress</button></div>

<div class="bs-example"><button id="popupProgressBootstrap" class="btn btn-primary">Bootstrap progress</button></div>

</fieldset>

<fieldset>

<div class="bs-example"><button id="popupWindowBasic" class="btn btn-primary">Window</button></div>

</fieldset>

</div>

<div>

<div class="bs-example">

### Custom buttons

<button id="popupProgressErrorButtons" class="btn btn-danger">Error</button></div>

</div>

<div>

<div class="bs-example">

### Disable icon

<button id="popupConfirmNoIcon" class="btn btn-primary">Button</button></div>

</div>

<div>

<div class="bs-example">

### Advanced usage of Lobibox.window

<button id="popupWindowExample" class="btn btn-primary">Window</button></div>

</div>

</div>

<div>

<div class="bs-example">

### Callbacks

<div class="callout callout-info">

All popup boxes have `callback` option

</div>

<button id="popupYesNoCallback" class="btn btn-primary">Confirm</button></div>

<div class="highlight">

    Lobibox.confirm({
        msg: "Are you sure you want to delete this user?",
        callback: function ($this, type, ev) {
            //Your code goes here
        }
    });        

</div>

</div>

<form id="lobibox-popup-demo-form" action="">

<div class="row">

<div class="col-sm-3">

<div class="form-group"><label class="control-label">Popup type</label> <select class="form-control" name="popupType"><option value="confirm">Confirm</option> <option value="alert">Alert</option> <option value="prompt">Prompt</option> <option value="progress">Progress</option></select></div>

</div>

</div>

<div class="panel panel-default">

<div class="panel-heading">

#### [Common parameters](#common-fieldset-wrapper)

</div>

<div id="common-fieldset-wrapper" class="panel-collapse collapse in">

<div class="panel-body">

<fieldset>

<div class="row">

<div class="col-sm-3">

<div class="form-group"><label class="control-label">title</label> <input type="text" name="title" class="form-control" value=""></div>

</div>

<div class="col-sm-3"><label class="control-label">Base class <small>(default)</small></label> <input type="text" name="baseClass" class="form-control" value="animated-super-fast"></div>

<div class="col-sm-3"><label class="control-label">Show class</label> <input type="text" name="showClass" class="form-control" value="zoomIn"></div>

<div class="col-sm-3"><label class="control-label">Hide class</label> <input type="text" name="hideClass" class="form-control" value="zoomOut"></div>

</div>

<div class="row">

<div class="col-sm-6"><label class="control-label">Message</label><textarea rows="4" class="form-control" name="msg"></textarea></div>

<div class="col-sm-3">

<div class="form-group"><label class="control-label">Width</label>

<div class="form-group"><input type="number" name="width" class="form-control"></div>

</div>

</div>

<div class="col-sm-3">

<div class="form-group"><label class="control-label">Height</label>

<div class="form-group"><input type="text" name="height" value="auto" class="form-control"></div>

</div>

</div>

</div>

<div class="row">

<div class="col-sm-3">

<div class="form-group"><label class="control-label"></label>

<div class="checkbox"><label><input type="checkbox" name="closeButton" checked=""> Close button</label> </div>

</div>

</div>

<div class="col-sm-3">

<div class="form-group"><label class="control-label"></label>

<div class="checkbox"><label><input type="checkbox" name="draggable"> Draggable</label> </div>

</div>

</div>

<div class="col-sm-3">

<div class="form-group"><label class="control-label"></label>

<div class="checkbox"><label><input type="checkbox" name="modal" checked=""> Modal</label> </div>

</div>

</div>

<div class="col-sm-3">

<div class="form-group"><label class="control-label"></label>

<div class="checkbox"><label><input type="checkbox" name="closeOnEsc"> Close on escape</label> </div>

</div>

</div>

</div>

</fieldset>

</div>

</div>

</div>

<div class="row">

<div class="col-md-12">

<div class="panel-group" id="accordion" role="tablist">

<div class="panel panel-default">

<div class="panel-heading" role="tab" id="headingOne">

#### [Confirm options](#confirm-options)

</div>

<div id="confirm-options" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">

<div class="panel-body">

<fieldset class="confirm-fieldset">

<div class="row">

<div class="col-md-4">

<div class="form-group"><label class="control-label">Icon Class</label> <input type="text" class="form-control" name="iconClass" value="glyphicon glyphicon-question-sign"></div>

</div>

</div>

</fieldset>

</div>

</div>

</div>

<div class="panel panel-default">

<div class="panel-heading" role="tab" id="headingTwo">

#### [Alert options](#alert-options)

</div>

<div id="alert-options" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">

<div class="panel-body">

<fieldset class="alert-fieldset" disabled="">

<div class="row">

<div class="col-md-4">

<div class="form-group"><label class="control-label">Alert type</label> <select class="form-control" name="type"><option value="success">Success</option> <option value="error">Error</option> <option value="info">Info</option> <option value="warning">Warning</option></select></div>

</div>

<div class="col-md-4">

<div class="form-group"><label class="control-label">Icon Class</label> <input type="text" class="form-control" name="iconClass"></div>

</div>

</div>

</fieldset>

</div>

</div>

</div>

<div class="panel panel-default">

<div class="panel-heading" role="tab">

#### [Prompt options](#prompt-options)

</div>

<div id="prompt-options" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">

<div class="panel-body">

<fieldset class="prompt-fieldset" disabled="">

<div class="row">

<div class="col-md-4">

<div class="form-group"><label class="control-label">Type</label> <input type="text" class="form-control" name="type" value="text"></div>

</div>

<div class="col-md-4">

<div class="form-group"><label class="control-label">Placeholder</label> <input type="text" class="form-control" name="placeholder" value=""></div>

</div>

<div class="col-md-4">

<div class="form-group"><label class="control-label">Value</label> <input type="text" class="form-control" name="value" value=""></div>

</div>

</div>

<div class="row">

<div class="col-md-4">

<div class="form-group"><label class="control-label">Label</label> <input type="text" class="form-control" name="label"></div>

</div>

<div class="col-md-4">

<div class="form-group"><label class="control-label"></label>

<div class="checkbox"><label><input type="checkbox" name="multiline"> Multiline</label> </div>

</div>

</div>

<div class="col-md-4">

<div class="form-group"><label class="control-label">Lines <small class="text-muted">(For multiline)</small></label> <input type="number" class="form-control" name="lines" value=""></div>

</div>

</div>

</fieldset>

</div>

</div>

</div>

<div class="panel panel-default">

<div class="panel-heading" role="tab">

#### [Progress options](#progress-options)

</div>

<div id="progress-options" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">

<div class="panel-body">

<div class="callout callout-danger">

Progress does not update itself.

But you can implement it easily when uploading or waiting something

</div>

<fieldset class="progress-fieldset" disabled="">

<div class="row">

<div class="col-md-4"><label class="control-label">Label</label> <input type="text" class="form-control" name="label" value=""></div>

<div class="col-md-4"><label class="control-label"></label>

<div class="checkbox"><label><input type="checkbox" name="showProgressLabel" checked=""> Progress label</label> </div>

</div>

</div>

</fieldset>

</div>

</div>

</div>

</div>

</div>

</div>

<button class="btn btn-primary">Create popup</button></form>

</div>

</div>

<div id="notifications">

<div id="lobibox-notification-examples">

### Examples

<fieldset><legend>Basic notifications <small class="text-muted"><small>Can be closed by clicking on it</small></small></legend>

<div class="bs-example"><button id="basicDefault" class="btn btn-default">Default</button> <button id="basicInfo" class="btn btn-info">Info</button> <button id="basicWarning" class="btn btn-warning">Warning</button> <button id="basicError" class="btn btn-danger">Error</button> <button id="basicSuccess" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>With image</legend>

<div class="bs-example"><button id="basicDefaultImage" class="btn btn-default">Default</button> <button id="basicInfoImage" class="btn btn-info">Info</button> <button id="basicWarningImage" class="btn btn-warning">Warning</button> <button id="basicErrorImage" class="btn btn-danger">Error</button> <button id="basicSuccessImage" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Disable sound</legend>

<div class="bs-example"><button id="basicInfoNoSound" class="btn btn-info">Info</button> <button id="basicWarningNoSound" class="btn btn-warning">Warning</button> <button id="basicErrorNoSound" class="btn btn-danger">Error</button> <button id="basicSuccessNoSound" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Custom title</legend>

<div class="bs-example"><button id="basicDefaultCustomTitle" class="btn btn-default">Default</button> <button id="basicInfoCustomTitle" class="btn btn-info">Info</button> <button id="basicWarningCustomTitle" class="btn btn-warning">Warning</button> <button id="basicErrorCustomTitle" class="btn btn-danger">Error</button> <button id="basicSuccessCustomTitle" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Without icon and image</legend>

<div class="bs-example"><button id="basicDefaultNoIcon" class="btn btn-default">Default</button> <button id="basicInfoNoIcon" class="btn btn-info">Info</button> <button id="basicWarningNoIcon" class="btn btn-warning">Warning</button> <button id="basicErrorNoIcon" class="btn btn-danger">Error</button> <button id="basicSuccessNoIcon" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Increase delay time</legend>

<div class="bs-example"><button id="basicDefaultCustomDelay" class="btn btn-default">Default</button> <button id="basicInfoCustomDelay" class="btn btn-info">Info</button> <button id="basicWarningCustomDelay" class="btn btn-warning">Warning</button> <button id="basicErrorCustomDelay" class="btn btn-danger">Error</button> <button id="basicSuccessCustomDelay" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Sticky (without delay)</legend>

<div class="bs-example"><button id="basicDefaultNoDelay" class="btn btn-default">Default</button> <button id="basicInfoNoDelay" class="btn btn-info">Info</button> <button id="basicWarningNoDelay" class="btn btn-warning">Warning</button> <button id="basicErrorNoDelay" class="btn btn-danger">Error</button> <button id="basicSuccessNoDelay" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Alternative position</legend>

<div class="bs-example"><button id="basicInfoPosition" class="btn btn-info">Info</button> <button id="basicWarningPosition" class="btn btn-warning">Warning</button> <button id="basicErrorPosition" class="btn btn-danger">Error</button> <button id="basicSuccessPosition" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Change width</legend>

<div class="bs-example"><button id="basicInfoWidth" class="btn btn-info">Info</button> <button id="basicWarningWidth" class="btn btn-warning">Warning</button> <button id="basicErrorWidth" class="btn btn-danger">Error</button> <button id="basicSuccessWidth" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Change Animation</legend>

For animation Lobibox is depended on animate.css. You can use any animate.css classes

By default `.animated` class is added

<div class="bs-example"><button id="basicInfoAnimation" class="btn btn-info">Info</button> <button id="basicWarningAnimation" class="btn btn-warning">Warning</button> <button id="basicErrorAnimation" class="btn btn-danger">Error</button> <button id="basicSuccessAnimation" class="btn btn-success">Success</button></div>

</fieldset>

## Large Notifications

<fieldset>

Large notifications

*   are sticky
*   can be closed only by clicking close button
*   does not have delay
*   are larger in width

<div class="bs-example"><button id="largeInfoBasic" class="btn btn-info">Info</button> <button id="largeWarningBasic" class="btn btn-warning">Warning</button> <button id="largeErrorBasic" class="btn btn-danger">Error</button> <button id="largeSuccessBasic" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset>

### With Image

<div class="bs-example"><button id="largeInfoImage" class="btn btn-info">Info</button> <button id="largeWarningImage" class="btn btn-warning">Warning</button> <button id="largeErrorImage" class="btn btn-danger">Error</button> <button id="largeSuccessImage" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Alternative position</legend>

<div class="bs-example"><button id="largeInfoPosition" class="btn btn-info">Info</button> <button id="largeWarningPosition" class="btn btn-warning">Warning</button> <button id="largeErrorPosition" class="btn btn-danger">Error</button> <button id="largeSuccessPosition" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset><legend>Change animation</legend>

<div class="bs-example"><button id="largeInfoAnimation" class="btn btn-info">Info</button> <button id="largeWarningAnimation" class="btn btn-warning">Warning</button> <button id="largeErrorAnimation" class="btn btn-danger">Error</button> <button id="largeSuccessAnimation" class="btn btn-success">Success</button></div>

</fieldset>

## Mini notifications

For mini notifications icon and image is shown on small size and title is disabled by default. Although you can enable it by giving `title` parameter when initializing.

<fieldset>

<div class="bs-example"><button id="miniDefaultAnimation" class="btn btn-default">Default</button> <button id="miniInfoAnimation" class="btn btn-info">Info</button> <button id="miniWarningAnimation" class="btn btn-warning">Warning</button> <button id="miniErrorAnimation" class="btn btn-danger">Error</button> <button id="miniSuccessAnimation" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset>

### With image

<div class="bs-example"><button id="miniDefaultImage" class="btn btn-default">Default</button> <button id="miniInfoImage" class="btn btn-info">Info</button> <button id="miniWarningImage" class="btn btn-warning">Warning</button> <button id="miniErrorImage" class="btn btn-danger">Error</button> <button id="miniSuccessImage" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset>

### Without icon

<div class="bs-example"><button id="miniDefaultNoIcon" class="btn btn-default">Default</button> <button id="miniInfoNoIcon" class="btn btn-info">Info</button> <button id="miniWarningNoIcon" class="btn btn-warning">Warning</button> <button id="miniErrorNoIcon" class="btn btn-danger">Error</button> <button id="miniSuccessNoIcon" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset>

### With title

<div class="bs-example"><button id="miniDefaultTitle" class="btn btn-default">Default</button> <button id="miniInfoTitle" class="btn btn-info">Info</button> <button id="miniWarningTitle" class="btn btn-warning">Warning</button> <button id="miniErrorTitle" class="btn btn-danger">Error</button> <button id="miniSuccessTitle" class="btn btn-success">Success</button></div>

</fieldset>

<fieldset>

### Rounded corners <span class="label label-danger">new</span>

<div class="bs-example"><button id="miniDefaultRounded" class="btn btn-default">Default</button> <button id="miniInfoRounded" class="btn btn-info">Info</button> <button id="miniWarningRounded" class="btn btn-warning">Warning</button> <button id="miniErrorRounded" class="btn btn-danger">Error</button> <button id="miniSuccessRounded" class="btn btn-success">Success</button></div>

</fieldset>

</div>

</div>

</div>

</div>
