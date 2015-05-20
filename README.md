heroku-buildpack-graphicsmagick
===============================

A Heroku buildpack that installs GraphicsMagick on the **Cedar-14** stack.  
The version currently installed is 1.3.18.  
See [config](config) for versions of lib dependencies.

Usage
-----

Simply add this Git repo to your `.buildpacks` file and set your Heroku config var `BUILDPACK_URL` to `https://github.com/mojodna/heroku-buildpack-multi.git#build-env`.
