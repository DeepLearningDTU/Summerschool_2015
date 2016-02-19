---
layout: post
comments: true
title: Install Theano on Windows
excerpt: Some guidelines for installing theano in windows
date: 2015-08-21T11:00:00.000Z
mathjax: true
published: true
---


Seems like quite a few people using windows computers have problems with installing and running Theano. Unfortunately we(TA's) only have experience with installing on Linux and MacOSX.

However it should be possible :)

To make theano work you will to
* NOT install CUDO eventhough you have a GPU, you won't need it and its seems to complicate installations quite a bit.
* The GCC compiler. See [here](http://deeplearning.net/software/theano/install_windows.html#gcc) for installation instructions.
* A python installation with numpy. WinPython seems like a good choice for theano. Follow instructions [here](http://deeplearning.net/software/theano/install_windows.html#scientific-python-distribution). After installation of python please check that you can import numpy in ipython.
* Theano should be shipped with WinPython - can some windows-user please confirm this?






