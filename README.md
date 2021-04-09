code-ini
========

Code Meta-Data for research software, scientific computing and computer-based experiments.

This is a curated list of research software projects providing code meta data,
proposed in "[JSON-LD for software discovery, reuse and credit](http://www.arfon.org/json-ld-for-software-discovery-reuse-and-credit)",
which facilitates replicability, reproducibility and reusability (RRR).

Using an [ini](https://en.wikipedia.org/wiki/INI_file)-file named `CODE` was suggested in:

[J. Heiland](https://orcid.org/0000-0003-0228-8522), [J. Fehr](https://orcid.org/0000-0003-2850-1440), [C. Himpe](https://orcid.org/0000-0003-2194-6754) and [J. Saak](https://orcid.org/0000-0001-5567-9637). Best Practices for Replicability, Reproducibility and Reusability of Computer-Based Experiments Exemplified by Model Reduction Software. AIMS Mathematics (AIMS Math) 1(3): 261--281, 2016. [doi:10.3934/Math.2016.3.261](http://doi.org/10.3934/Math.2016.3.261)

An additional benefit is the visibility and discoverability of scientific source codes.
Add yours!

## Sample Keys

`name:` project name  
`shortname:` executable or abbreviated project name  
`version:` project version number: major.minor.patch  
`release-date:` version release date in ISO 8601 format: yyyy-mm-dd  
`id:` project version identifier  
`id-type:` identifier type, i.e.: doi  
`author:` comma separated list of author names  
`orcid:` comma separated list of author ORCIDs  
`topic:` dmoz.org categorization of project  
`type:` project type, i.e.: application, library, toolbox  
`license:` opensource.org name of project license  
`license-type:` license classification, i.e.: open, copy-left  
`repository:` url of project repository  
`repository-type:` repository protocol, i.e.: git  
`language:` comma separated list of utilized programming languages  
`dependencies:` comma separated list of dependencies with versions, ie: Octave >=4.2, Matlab >=2016b  
`systems:` comma separated list of compatible operating systems, i.e.: Windows, Linux  
`website:` url of project website  
`keywords:` comma separated list of (up to five) keywords

### Field Values

It is recommended to use only [printable ASCII characters](https://en.wikipedia.org/wiki/ASCII#Printable_characters).

### Declaration Header

Optionally, a **code-ini** declaration may be included as a first line:

`# code.ini`

### File Format

Use a plain text, UTF-8 encoded file. 

## Research Software Projects:

* `c-mess` [C Matrix Equations Sparse Solvers](https://www.mpi-magdeburg.mpg.de/projects/mess) [[code.ini](https://gitlab.mpi-magdeburg.mpg.de/mess/cmess-releases/blob/master/CODE)]
* `emgr` [EMpirical GRamian Framework](https://gramian.de) [[code.ini](http://github.com/gramian/emgr/blob/master/CODE)]
* `flexiblas` [FlexiBLAS - A runtime BLAS switch](https://www.mpi-magdeburg.mpg.de/projects/flexiblas) [[code.ini](https://gitlab.mpi-magdeburg.mpg.de/software/flexiblas-release/raw/master/CODE)]
* `granso` [GRadient-based Algorithm for Non-Smooth Optimization](http://www.timmitchell.com/software/GRANSO/) [[code.ini](https://gitlab.com/timmitchell/GRANSO/blob/master/code.ini)]
* `hapod` [HAPOD - Hierarchical Approximate Proper Orthogonal Decomposition](https://github.com/gramian/hapod/) [[code.ini](https://github.com/gramian/hapod/blob/master/CODE)]
* `morlab` [Model Order Reduction LABoratory](https://www.mpi-magdeburg.mpg.de/projects/morlab)
* `m-mess` [MATLAB Matrix Equations Sparse Solvers](https://www.mpi-magdeburg.mpg.de/projects/mess) [[code.ini](https://gitlab.mpi-magdeburg.mpg.de/mess/mmess-releases/blob/v1.0.1/CODE)]
* `morgen` [morgen - Model Order Reduction for Gas and Energy Networks](https://github.com/mpimd-csc/morgen) [[code.ini](https://github.com/mpimd-csc/morgen/blob/master/CODE)]
* `qrupdate-ng` [A FORTRAN library for rank-1 matrix decomposition updates](https://github.com/mpimd-csc/qrupdate-ng) [[code.ini](https://github.com/mpimd-csc/qrupdate-ng/blob/master/CODE)]
* `rostapack` [RObust STAbility PACKage](http://www.timmitchell.com/software/ROSTAPACK/index.html) [[code.ini](https://gitlab.com/timmitchell/ROSTAPACK/blob/master/code.ini)]
* `solbt` [Limited Balanced Truncation for Large-Scale Sparse Second-Order Systems](https://doi.org/10.5281/zenodo.4600763)
* `somddpa` [Second-Order Modally-Damped Dominant Pole Algorithm](https://doi.org/10.5281/zenodo.2553901)

## Get the Shield Badge:

![code meta-data shield](https://img.shields.io/badge/code_meta--data-%E2%9C%93-brightgreen.svg)

`![code meta-data shield](https://img.shields.io/badge/code_meta--data-%E2%9C%93-brightgreen.svg)`

Automatized CODE check is planned.

## See Also:

* [codemeta](https://github.com/codemeta/codemeta)
* [setup.py](https://docs.python.org/3/distutils/setupscript.html#additional-meta-data)
* [.desktop](https://standards.freedesktop.org/desktop-entry-spec/desktop-entry-spec-latest.html)
* [gem spec](https://guides.rubygems.org/specification-reference/)
