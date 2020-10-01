# serf-win-build

Apache serf Windows build with Visual Studio.

This version is serf-1.3.9.

To build, simply open the required solution file, and
you know how to use Visual Studio, right?
(or perhaps this is the wrong place for you.)

Depends on:
* libiconv-win-build  
* zlib-win-build  
* openssl1_1-win-build  
* expat-win-build  
* apr-win-build  
* apr-util-win-build  

There are hard references assuming all these sit next to serf-win-build.

Basically, in a command prompt:

> \> cd {somewhere}\\  
> \> git clone https://github.com/kiyolee/libiconv-win-build.git  
> \> git clone https://github.com/kiyolee/zlib-win-build.git  
> \> git clone https://github.com/kiyolee/openssl1_1-win-build.git  
> \> git clone https://github.com/kiyolee/expat-win-build.git  
> \> git clone https://github.com/kiyolee/apr-win-build.git  
> \> git clone https://github.com/kiyolee/apr-util-win-build.git  
> \> git clone https://github.com/kiyolee/serf-win-build.git  

Build all these dependencies in the suggested order as shown above and finally serf, with the same corresponding Visual Studio solution of course.
