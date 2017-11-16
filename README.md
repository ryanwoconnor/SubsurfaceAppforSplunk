# SubsurfaceAppforSplunk

You should setup an input stanza like the following. This way anytime you save your divelog, it will be indexed and all dashboards in the app will work correctly:

 [monitor:///Path/To/Your/log.xml]
 index=subsurface
 sourcetype=subsurface
