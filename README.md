SeleniumDownloadHelper
======================

It is still WIP but Chrome, Safari, Firefox, PhantomJS and Internet Explorer are working so far with this method.
IE only tested on MS Windows and Safari only on OSX.

HTMLUnit is not working but the why is still open (expected.length=187514 actual.length=176549).
Maybe a bug in RhinoJS which messes up the base64 conversion or some early return in the XHR call?

Usage
=============
@see src/test/java/ch/racic/selenium/helper/download/SeleniumDownloadHelperTest.java

Maven Central
=============
```xml
<dependency>
    <groupId>ch.racic.selenium.helper</groupId>
    <artifactId>SeleniumDownloadHelper</artifactId>
    <version>0.3.2</version>
</dependency>
```
