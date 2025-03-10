About google-cloud-vision
=========================

Home: https://github.com/googleapis/google-cloud-python

Package license: Apache 2.0

Feedstock license: BSD 3-Clause

Summary: Python Client for Google Cloud Vision

Python Client for Google Cloud Vision
-------------------------

The [Google Cloud Vision](https://cloud.google.com/vision/) API enables developers to
understand the content of an image by encapsulating powerful machine
learning models in an easy to use REST API. It quickly classifies images
into thousands of categories (e.g., "sailboat", "lion", "Eiffel Tower"),
detects individual objects and faces within images, and finds and reads
printed words contained within images. You can build metadata on your
image catalog, moderate offensive content, or enable new marketing
scenarios through image sentiment analysis. Analyze images uploaded
in the request or integrate with your image storage on Google Cloud
Storage.

- [Client Library Documentation](https://googleapis.github.io/google-cloud-python/latest/vision/)
- [Product Documentation](https://cloud.google.com/vision/reference/rest/)

Quick Start
-----------

In order to use this library, you first need to go through the following steps:

1. [Select or create a Cloud Platform project.](https://console.cloud.google.com/project)
2. [Enable billing for your project.](https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project)
3. [Enable the Google Cloud Language API.](https://cloud.google.com/natural-language)
4. [Setup Authentication.](https://googleapis.github.io/google-cloud-python/latest/core/auth.html)

Supported Python Versions
-----------
Python >= 3.5

Deprecated Python Versions
-----------
Python == 2.7. Python 2.7 support will be removed on January 1, 2020.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_python2.7</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=linux&configuration=linux_python2.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.6</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=linux&configuration=linux_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.7</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=linux&configuration=linux_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.8</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=linux&configuration=linux_python3.8" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python2.7</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=osx&configuration=osx_python2.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.6</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=osx&configuration=osx_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.7</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=osx&configuration=osx_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.8</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=osx&configuration=osx_python3.8" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.6vc14</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=win&configuration=win_python3.6vc14" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.7vc14</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=win&configuration=win_python3.7vc14" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.8vc14</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6613&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/google-cloud-vision-feedstock?branchName=master&jobName=win&configuration=win_python3.8vc14" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-google--cloud--vision-green.svg)](https://anaconda.org/conda-forge/google-cloud-vision) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/google-cloud-vision.svg)](https://anaconda.org/conda-forge/google-cloud-vision) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/google-cloud-vision.svg)](https://anaconda.org/conda-forge/google-cloud-vision) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/google-cloud-vision.svg)](https://anaconda.org/conda-forge/google-cloud-vision) |

Installing google-cloud-vision
==============================

Installing `google-cloud-vision` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `google-cloud-vision` can be installed with:

```
conda install google-cloud-vision
```

It is possible to list all of the versions of `google-cloud-vision` available on your platform with:

```
conda search google-cloud-vision --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating google-cloud-vision-feedstock
======================================

If you would like to improve the google-cloud-vision recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/google-cloud-vision-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@BrentDorsey](https://github.com/BrentDorsey/)

