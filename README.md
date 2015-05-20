:exclamation: The Cedar-14 stack is now supported by [`https://github.com/mcollina/heroku-buildpack-graphicsmagick`](https://github.com/mcollina/heroku-buildpack-graphicsmagick), so please use that buildpack instead.

heroku-buildpack-graphicsmagick
===============================
:exclamation: **PNG support is currently broken in the compiled binary.** JPEG support is unaffected.

A Heroku buildpack that installs GraphicsMagick on the **Cedar-14** stack.  
The version currently installed is 1.3.20.  
See [config](config) for versions of lib dependencies.

Usage
-----

Simply add this Git repo to your `.buildpacks` file and set your Heroku config var `BUILDPACK_URL` to `https://github.com/mojodna/heroku-buildpack-multi.git#build-env`.

Sources
-------

Source files were downloaded from the following locations and compiled on Cedar-14:
````
http://zlib.net/zlib-1.2.8.tar.gz
http://www.nasm.us/pub/nasm/releasebuilds/2.11.06/nasm-2.11.06.tar.gz
http://downloads.sourceforge.net/project/libpng/libpng16/1.6.16/libpng-1.6.16.tar.gz
http://sourceforge.net/projects/libjpeg-turbo/files/1.4.0/libjpeg-turbo-1.4.0.tar.gz
http://sourceforge.net/projects/graphicsmagick/files/graphicsmagick/1.3.20/GraphicsMagick-1.3.20.tar.bz2
````
