# Vagrant Box based on ubuntu 15.10 (64bit)

This box is configured with X forwarding, so remember to connect to it with ```vagrant -Y ssh```.

__Comes with:__

* OpenCV 3.1.0
* Python 3.4 (ipython)
* virtualenv

__Usage:__

```
vagrant up # This might take a while the first time around (compiling opencv, etc.)
vagrant -Y ssh
workon cv
```

__MacOSX__:

You will have to install XQuartz (http://www.xquartz.org/).
