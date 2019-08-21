About llvm-openmp
=================

Home: http://openmp.llvm.org/

Package license: NCSA

Feedstock license: BSD 3-Clause

Summary: The OpenMP API supports multi-platform shared-memory parallel programming in C/C++ and Fortran.



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=67&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/llvm-openmp-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=67&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/llvm-openmp-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=67&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/llvm-openmp-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_cxx_compilervs2015vc14</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=67&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/llvm-openmp-feedstock?branchName=master&jobName=win&configuration=win_cxx_compilervs2015vc14" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-llvm--openmp-green.svg)](https://anaconda.org/nsls2forge/llvm-openmp) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/llvm-openmp.svg)](https://anaconda.org/nsls2forge/llvm-openmp) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/llvm-openmp.svg)](https://anaconda.org/nsls2forge/llvm-openmp) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/llvm-openmp.svg)](https://anaconda.org/nsls2forge/llvm-openmp) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openmp-green.svg)](https://anaconda.org/nsls2forge/openmp) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/openmp.svg)](https://anaconda.org/nsls2forge/openmp) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/openmp.svg)](https://anaconda.org/nsls2forge/openmp) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/openmp.svg)](https://anaconda.org/nsls2forge/openmp) |

Installing llvm-openmp
======================

Installing `llvm-openmp` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `llvm-openmp, openmp` can be installed with:

```
conda install llvm-openmp openmp
```

It is possible to list all of the versions of `llvm-openmp` available on your platform with:

```
conda search llvm-openmp --channel nsls2forge
```




Updating llvm-openmp-feedstock
==============================

If you would like to improve the llvm-openmp recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/llvm-openmp-feedstock are
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

* [@inducer](https://github.com/inducer/)
* [@isuruf](https://github.com/isuruf/)
* [@jakirkham](https://github.com/jakirkham/)
* [@yesimon](https://github.com/yesimon/)
