Backbone.setMode
================

Backbone plugin: setMode.
Forked from [DocumentSource](https://github.com/documentcloud/documentcloud/blob/master/public/javascripts/lib/backbone_extensions.js#L8)

Makes the view enter a mode. Modes have both a 'mode' and a 'group',
and are mutually exclusive with any other modes in the same group.
Setting will update the view's modes hash, as well as set an HTML class
of *[mode]_[group]* on the view's element. Convenient way to swap styles
and behavior.
