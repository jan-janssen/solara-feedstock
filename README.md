About solara-feedstock
======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/solara-feedstock/blob/main/LICENSE.txt)


About solara
------------

Home: https://github.com/widgetti/solara

Package license: MIT AND BSD-3-Clause

Summary: A Pure Python, React-style Framework for Scaling Your Jupyter and Web Apps

About solara-assets
-------------------



Package license: MIT AND BSD-3-Clause AND Apache-2.0

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <a href="https://github.com/conda-forge/solara-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/solara-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-solara-green.svg)](https://anaconda.org/conda-forge/solara) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/solara.svg)](https://anaconda.org/conda-forge/solara) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/solara.svg)](https://anaconda.org/conda-forge/solara) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/solara.svg)](https://anaconda.org/conda-forge/solara) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-solara--assets-green.svg)](https://anaconda.org/conda-forge/solara-assets) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/solara-assets.svg)](https://anaconda.org/conda-forge/solara-assets) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/solara-assets.svg)](https://anaconda.org/conda-forge/solara-assets) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/solara-assets.svg)](https://anaconda.org/conda-forge/solara-assets) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-solara--server-green.svg)](https://anaconda.org/conda-forge/solara-server) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/solara-server.svg)](https://anaconda.org/conda-forge/solara-server) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/solara-server.svg)](https://anaconda.org/conda-forge/solara-server) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/solara-server.svg)](https://anaconda.org/conda-forge/solara-server) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-solara--ui-green.svg)](https://anaconda.org/conda-forge/solara-ui) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/solara-ui.svg)](https://anaconda.org/conda-forge/solara-ui) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/solara-ui.svg)](https://anaconda.org/conda-forge/solara-ui) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/solara-ui.svg)](https://anaconda.org/conda-forge/solara-ui) |

Installing solara
=================

Installing `solara` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install solara solara-assets solara-server solara-ui
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install solara solara-assets solara-server solara-ui
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add solara solara-assets solara-server solara-ui
# for installing globally
pixi global install solara solara-assets solara-server solara-ui
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `solara` available on your platform:

<details>
<summary>With conda</summary>

```
conda search solara --channel conda-forge
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search solara --channel conda-forge
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search solara --channel conda-forge
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search solara --channel conda-forge

# List packages depending on `solara`:
mamba repoquery whoneeds solara --channel conda-forge

# List dependencies of `solara`:
mamba repoquery depends solara --channel conda-forge
```

</details>


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating solara-feedstock
=========================

If you would like to improve the solara recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/solara-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@dhirschfeld](https://github.com/dhirschfeld/)
* [@iisakkirotko](https://github.com/iisakkirotko/)
* [@maartenbreddels](https://github.com/maartenbreddels/)
* [@mariobuikhuizen](https://github.com/mariobuikhuizen/)

