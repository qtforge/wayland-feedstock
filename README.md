About wayland
=============

Home: https://gitlab.freedesktop.org/wayland/wayland

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/wayland-feedstock/blob/main/LICENSE.txt)

Summary: Base libraries for the Wayland rendering architecture

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/wayland-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/wayland-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/wayland-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/wayland-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-wayland-green.svg)](https://anaconda.org/qtforge/wayland) | [![Conda Downloads](https://img.shields.io/conda/dn/qtforge/wayland.svg)](https://anaconda.org/qtforge/wayland) | [![Conda Version](https://img.shields.io/conda/vn/qtforge/wayland.svg)](https://anaconda.org/qtforge/wayland) | [![Conda Platforms](https://img.shields.io/conda/pn/qtforge/wayland.svg)](https://anaconda.org/qtforge/wayland) |

Installing wayland
==================

Installing `wayland` from the `qtforge` channel can be achieved by adding `qtforge` to your channels with:

```
conda config --add channels qtforge
conda config --set channel_priority strict
```

Once the `qtforge` channel has been enabled, `wayland` can be installed with `conda`:

```
conda install wayland
```

or with `mamba`:

```
mamba install wayland
```

It is possible to list all of the versions of `wayland` available on your platform with `conda`:

```
conda search wayland --channel qtforge
```

or with `mamba`:

```
mamba search wayland --channel qtforge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search wayland --channel qtforge

# List packages depending on `wayland`:
mamba repoquery whoneeds wayland --channel qtforge

# List dependencies of `wayland`:
mamba repoquery depends wayland --channel qtforge
```




Updating wayland-feedstock
==========================

If you would like to improve the wayland recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`qtforge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `qtforge` channel.
Note that all branches in the conda-forge/wayland-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@hmaarrfk](https://github.com/hmaarrfk/)

