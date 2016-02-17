# iframeActivationListener
This jquery plugin triggers an "activate" event, when an iframe gets the focus

### How to use
To enable this event for an iFrame, call the iframeActivationListener function on that jquery-iframe object.

### Example
  $(document).ready(function ()
  {
      $('iframe').iframeActivationListener();
      $('iframe').on("activate", function(ev) {
  	      console.log($(ev.target));
      });
  });

Live Example: http://jsfiddle.net/56g7uLub/4/
