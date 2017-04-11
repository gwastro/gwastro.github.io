## Getting Started

PyCBC is a package used to explore astrophysical sources of gravitational waves. It contains algorithms that can detect signals using LIGO and measure the astrophysical parameters of detected sources. PyCBC was used in the first direct detection of gravitational waves (GW150914) and is used in the ongoing analysis of LIGO and Virgo data.

The easiest way to start using PyCBC is to install one of our [Docker containers.](https://hub.docker.com/u/pycbc/). Install the [Docker Community Edition](https://www.docker.com/community-edition) for your [Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac?tab=description) or [Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows?tab=description) desktop, then type the commands shown below. Docker CE installations for [Linux platforms](https://www.docker.com/community-edition#/download) are also available.

<script src="https://raw.githubusercontent.com/mattboldt/typed.js/v1.1.7/js/typed.js" charset="utf-8"></script>
<script type="text/javascript">
	document.addEventListener("DOMContentLoaded", function(){
		Typed.new(".element", {
			strings: ["docker pull pycbc/pycbc-el7:v1.7.0<br>$^500 docker run -it pycbc/pycbc-el7:v1.7.0 /bin/bash -l^1000<br>&#40;pycbc-software&#41;&#91;pycbc@37184573e664 &#126;&#93;$^500 python<br>Python 2.7.5 &#40;default, Nov  6 2016, 00:28:07&#41;<br>&#91;GCC 4.8.5 20150623 &#40;Red Hat 4.8.5-11&#41;&#93; on linux2<br>&gt;&gt;&gt; ^500import pycbc.version<br>&gt;&gt;&gt; ^500print pycbc.version.git_tag<br>v1.7.0<br>&gt;&gt;&gt; ^500import lal.git_version<br>&gt;&gt;&gt; ^500print lal.git_version.id<br>539c8700af92eb6dd00e0e91b9dbaf5bae51f004<br>&gt;&gt;&gt; "],
			typeSpeed: 0
		});
	});
</script>

<div class="text-editor-wrap">
		<div class="title-bar"><span class="title">pycbc &mdash; bash &mdash; 80x<span class="terminal-height">25</span></span></div>
		<div class="text-body">
			$ <span class="element"></span>
		</div>
</div>


## Documentation

See the [latest documentation](pycbc/latest/html/) built from the [source code](https://github.com/ligo-cbc/pycbc)

[![PyPI version](https://badge.fury.io/py/PyCBC.svg)](https://badge.fury.io/py/PyCBC)
[![Build Status](https://travis-ci.org/ligo-cbc/pycbc.svg?branch=master)](https://travis-ci.org/ligo-cbc/pycbc)
[![Code Health](https://landscape.io/github/ligo-cbc/pycbc/master/landscape.svg?style=flat)](https://landscape.io/github/ligo-cbc/pycbc/master)
[![Research software impact](http://depsy.org/api/package/pypi/PyCBC/badge.svg)](http://depsy.org/package/python/PyCBC)

## Use of PyCBC in Scientific Publications

If you use any code from PyCBC in a scientific publication, then we ask that
it is cited in the following way:

```
These results were generated using the PyCBC software package
\cite{Canton:2014ena,Usman:2015kfa,pycbc-software}
```

For the citation ``pycbc-software``,  please use a bibtex entry and DOI for the
appropriate release of the PyCBC software (or the latest available release).
A bibtex key and DOI for each release is avaliable from [Zenodo](http://zenodo.org/).
A key for the latest release is available at:

[![DOI](https://zenodo.org/badge/31596861.svg)](https://zenodo.org/badge/latestdoi/31596861)

Bibtex keys for the citations ``Canton:2014ena`` and ``Usman:2015kfa`` are

```
@article{Canton:2014ena,
      author         = "Dal Canton, Tito and others",
      title          = "{Implementing a search for aligned-spin neutron
                        star-black hole systems with advanced ground based
                        gravitational wave detectors}",
      journal        = "Phys. Rev.",
      volume         = "D90",
      year           = "2014",
      number         = "8",
      pages          = "082004",
      doi            = "10.1103/PhysRevD.90.082004",
      eprint         = "1405.6731",
      archivePrefix  = "arXiv",
      primaryClass   = "gr-qc",
      reportNumber   = "LIGO-P1400053",
      SLACcitation   = "%%CITATION = ARXIV:1405.6731;%%"
}

@article{Usman:2015kfa,
      author         = "Usman, Samantha A. and others",
      title          = "{The PyCBC search for gravitational waves from compact
                        binary coalescence}",
      journal        = "Class. Quant. Grav.",
      volume         = "33",
      year           = "2016",
      number         = "21",
      pages          = "215004",
      doi            = "10.1088/0264-9381/33/21/215004",
      eprint         = "1508.02357",
      archivePrefix  = "arXiv",
      primaryClass   = "gr-qc",
      reportNumber   = "LIGO-P1500086",
      SLACcitation   = "%%CITATION = ARXIV:1508.02357;%%"
}
```

