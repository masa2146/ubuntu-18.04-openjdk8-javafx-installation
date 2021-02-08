# ubuntu-18.04-openjdk8-javafx-installation
## Install Open JDK 8

``` sudo apt-get update 
 sudo apt install openjdk-8-jdk 
```

## Install openjfx

The default openjfx package on Ubuntu 18.04 is not compatible with OpenJDK 8. 
You may use the older version of the openjfx package. 
Please note that it's not a fully secure solution because you won't get updates for the package.

``` sudo apt install \
  openjfx=8u161-b12-1ubuntu2 \
  libopenjfx-java=8u161-b12-1ubuntu2 \
  libopenjfx-jni=8u161-b12-1ubuntu2
```
Hold the package:

```
sudo apt-mark hold \
  openjfx \
  libopenjfx-java \
  libopenjfx-jni
```
