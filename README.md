AnimatedGifImage for Flex 4
===========================

Description
-----------

This component utilizes spark.Image to display animated GIF via [as3gif](http://code.google.com/p/as3gif/ "as3gif"). 

Installation
------------

* Add [as3gif](http://code.google.com/p/as3gif/ "as3gif") to your project;
* Copy AnimatedGifImage.mxml to your project.

Usage example
-------------

```mxml
<component:AnimatedGifImage source="http://some.url/some.gif" width="100%" height="100%" scaleMode="stretch" fillMode="scale" />
<component:AnimatedGifImage source="{_source}" width="100%" height="100%" scaleMode="stretch" fillMode="scale" />
```

*_source* may be URL or ByteArray.