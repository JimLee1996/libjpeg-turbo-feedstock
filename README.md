About libjpeg-turbo
===================

Home: http://www.libjpeg-turbo.org/

Package license: IJG, modified 3-clause BSD and zlib

Feedstock license: BSD 3-Clause

Summary: IJG JPEG compliant runtime library with SIMD and other optimizations
Can be mixed with libjpeg >= 9:
  - Library files live in custom locations
  - Public symbols are prefixed with "turbo_"
  - Provided headers allow to keep using standard libjpeg API




Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/loopbio/libjpeg-turbo-feedstock/master.svg?label=Linux)](https://circleci.com/gh/loopbio/libjpeg-turbo-feedstock)
![OSX disabled](https://img.shields.io/badge/OSX-disabled-lightgrey.svg)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libjpeg--turbo-green.svg)](https://anaconda.org/loopbio/libjpeg-turbo) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/libjpeg-turbo.svg)](https://anaconda.org/loopbio/libjpeg-turbo) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/libjpeg-turbo.svg)](https://anaconda.org/loopbio/libjpeg-turbo) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/libjpeg-turbo.svg)](https://anaconda.org/loopbio/libjpeg-turbo) |

Installing libjpeg-turbo
========================

Installing `libjpeg-turbo` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `libjpeg-turbo` can be installed with:

```
conda install libjpeg-turbo
```

It is possible to list all of the versions of `libjpeg-turbo` available on your platform with:

```
conda search libjpeg-turbo --channel loopbio
```




Updating libjpeg-turbo-feedstock
================================

If you would like to improve the libjpeg-turbo recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/libjpeg-turbo-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.