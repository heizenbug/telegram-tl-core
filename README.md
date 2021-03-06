Type Language core java library
================
Contains basic classes for working with TL Serialization.

This implementation contains minimul required subset of TL for working with telegraph.org messaging service.

[![TL Core build server](http://ci.81port.com/app/rest/builds/buildType:%28id:TypeLanguage_JavaTlCore%29/statusIcon)](http://ci.81port.com/viewType.html?buildTypeId=TypeLanguage_JavaTlCore)

Gradle
----------------
###### Include our repository
````
respository {
  maven {
    url "http://maven.81port.com/archiva/repository/internal/"
  }
}
````

###### Include tl-core
````
dependencies {
  ...
  compile "org.telegram:tl-core:1.0.+"
  ...
}
````

More information
----------------
#### Type Language documentation

English: http://core.telegram.org/mtproto/TL

Russian: http://dev.stel.com/mtproto/TL

####Telegraph project

http://telegram.org/

#### Android Client that uses this library

[![Telegram S](https://developer.android.com/images/brand/en_generic_rgb_wo_45.png)](https://play.google.com/store/apps/details?id=org.telegram.android "Telegram S")

Licence
----------------
This library uses [MIT Licence](LICENCE)
