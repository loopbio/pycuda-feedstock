About pycuda
============

Home: http://pypi.python.org/pypi/pycuda

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: Python wrapper for CUDA

PyCUDA lets you access GPUs from Python, through the CUDA parallel
compute interface.


Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/loopbio/pycuda-feedstock.svg?style=shield)](https://circleci.com/gh/loopbio/pycuda-feedstock)
OSX: ![](https://cdn.rawgit.com/conda-forge/conda-smithy/90845bba35bec53edac7a16638aa4d77217a3713/conda_smithy/static/disabled.svg)
Windows: ![](https://cdn.rawgit.com/conda-forge/conda-smithy/90845bba35bec53edac7a16638aa4d77217a3713/conda_smithy/static/disabled.svg)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/loopbio/pycuda/badges/version.svg)](https://anaconda.org/loopbio/pycuda)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/loopbio/pycuda/badges/downloads.svg)](https://anaconda.org/loopbio/pycuda)

Installing pycuda
=================

Installing `pycuda` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `pycuda` can be installed with:

```
conda install pycuda
```

It is possible to list all of the versions of `pycuda` available on your platform with:

```
conda search pycuda --channel loopbio
```




Updating pycuda-feedstock
=========================

If you would like to improve the pycuda recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/pycuda-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
