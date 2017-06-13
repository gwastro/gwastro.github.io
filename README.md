PyCBC is a software package used to explore astrophysical sources of gravitational waves. It contains algorithms that can detect coalescing compact binaries and measure the astrophysical parameters of detected sources. PyCBC was used in the [first direct detection of gravitational waves by LIGO](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.061102) and is used in the ongoing analysis of LIGO and Virgo data.  PyCBC was featured in [Physics World](http://live.iop-pp01.agh.sleek.net/2017/02/26/why-we-should-give-credit-to-code%E2%80%AFcreators/) as a good example of a large collaboration publishing its research products, including its software.

## Getting Started
You can start using the PyCBC library now in an interactive notebook!

[![azure](https://img.shields.io/badge/azure-notebook-pi.svg)](https://notebooks.azure.com/nitz/libraries/pycbc)
[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/ligo-cbc/binder)

The easiest way to start using PyCBC on your computer is to install one of our [Docker containers.](https://hub.docker.com/u/pycbc/) Install the [Docker Community Edition](https://www.docker.com/community-edition) for your [Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac?tab=description) or [Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows?tab=description) desktop, then type the commands shown below. Docker CE installations for [Linux platforms](https://www.docker.com/community-edition#/download) are also available.

<script src="https://raw.githubusercontent.com/mattboldt/typed.js/v1.1.7/js/typed.js" charset="utf-8"></script>
<script type="text/javascript">
	document.addEventListener("DOMContentLoaded", function(){
		Typed.new(".element", {
			strings: ["^500<strong>docker pull pycbc/pycbc-el7:latest</strong><br>$ ^500<strong>docker run -it pycbc/pycbc-el7:latest /bin/bash -l</strong><br>&#40;pycbc-software&#41;&#91;pycbc@37184573e664 &#126;&#93;$ ^500<strong>python</strong><br>Python 2.7.5 &#40;default, Nov  6 2016, 00:28:07&#41;<br>&#91;GCC 4.8.5 20150623 &#40;Red Hat 4.8.5-11&#41;&#93; on linux2<br>&gt;&gt;&gt; ^500<strong>execfile&#40;&quot;/home/pycbc/src/pycbc/examples/waveform/match_waveform.py&quot;&#41;</strong><br>^1000The match is: 0.953<br>&gt;&gt;&gt; ^500<strong>from pycbc.waveform import td_approximants</strong><br>&gt;&gt;&gt; ^500<strong>print td_approximants&#40;&#41;&#91;20:24&#93;</strong><br>['SEOBNRv3', 'SEOBNRv2', 'SpinTaylorT1', 'SEOBNRv4']<br>&gt;&gt;&gt; "],
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

[![DOI](https://zenodo.org/badge/31596861.svg)](https://zenodo.org/badge/latestdoi/31596861)
[![PyPI version](https://badge.fury.io/py/PyCBC.svg)](https://badge.fury.io/py/PyCBC)
[![Build Status](https://travis-ci.org/ligo-cbc/pycbc.svg?branch=master)](https://travis-ci.org/ligo-cbc/pycbc)
[![Code Health](https://landscape.io/github/ligo-cbc/pycbc/master/landscape.svg?style=flat)](https://landscape.io/github/ligo-cbc/pycbc/master)
[![Research software impact](http://depsy.org/api/package/pypi/PyCBC/badge.svg)](http://depsy.org/package/python/PyCBC)

## Documentation

See the [latest documentation](pycbc/latest/html/) built from the [source code](https://github.com/ligo-cbc/pycbc) for more instructions on how to get started, including setting up a Docker container that can [display graphics](http://ligo-cbc.github.io/pycbc/latest/html/docker.html) from PyCBC programs.

If you use PyCBC in your scientific publications or projects, we ask that you acknowlege our work by citing the publications that describe  PyCBC and the software's [digital object identifier](https://zenodo.org/badge/latestdoi/31596861), as described in the
 [PyCBC citation guidelines.](http://ligo-cbc.github.io/pycbc/latest/html/credit.html)

## Scientific Publications

#### Observational Results ####
 * [Observation of Gravitational Waves from a Binary Black Hole Merger.](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.061102)
 * [GW151226: Observation of Gravitational Waves from a 22-Solar-Mass Binary Black Hole Coalescence.](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.241103)
 * [The Rate of Binary Black Hole Mergers Inferred from Advanced LIGO Observations Surrounding GW150914.](http://iopscience.iop.org/article/10.3847/2041-8205/833/1/L1/meta)
 * [Supplement: The Rate of Binary Black Hole Mergers Inferred from Advanced LIGO Observations Surrounding GW150914](http://iopscience.iop.org/article/10.3847/0067-0049/227/2/14/meta)
 * [Binary Black Hole Mergers in the first Advanced LIGO Observing Run.](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.6.041015)
  * [GW170104: Observation of a 50-Solar-Mass Binary Black Hole Coalescence at Reshift 0.2](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.118.221101)

#### Technical and Methods Papers ####
 * Detecting binary compact-object mergers with gravitational waves: Understanding and Improving the sensitivity of the PyCBC search. Free prerint at [arXiv:1705.01513](https://arxiv.org/abs/1705.01513)
 * [The PyCBC search for gravitational waves from compact binary coalescence.](http://iopscience.iop.org/article/10.1088/0264-9381/33/21/215004/meta;jsessionid=287B432D6C1C3583375F20A3C7EE6DD8.ip-10-40-1-105) Free preprint at [arXiv:1508.02357](https://arxiv.org/abs/1508.02357)
 * [Implementing a search for aligned-spin neutron star-black hole systems with advanced ground based gravitational wave detectors.](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.90.082004) Free preprint at [arXiv:1405.6731](https://arxiv.org/abs/1405.6731)
 * [Validating gravitational-wave detections: The Advanced LIGO hardware injection system.](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.95.062002) Free preprint at [arXiv:1612.07864](https://arxiv.org/abs/1612.07864)

## In the News

 * [Why we should give credit to code creators](http://iopscience.iop.org/article/10.1088/2058-7058/30/3/37/pdf), March 2017, Physics World.
  * [High throughput computing helps LIGO confirm Einstein's last unproven theory](https://phys.org/news/2016-03-high-throughput-ligo-einstein-unproven.html), March 9, 2016, Phys.org.
  * [XSEDE Resources Help Confirm LIGO Discovery](https://www.xsede.org/xsede-resources-help-confirm-ligo-discovery), NSF Extreme Science and Engineering Discovery Environment.
  * [OSG helps LIGO scientists confirm Einstein’s unproven theory](https://www.opensciencegrid.org/osg-helps-ligo-scientists-confirm-einsteins-last-unproven-theory/), OSG press release.
  * [Science Powerhouses Unite to Help Search for Gravitational Waves](https://www.tacc.utexas.edu/-/science-powerhouses-unite-to-help-search-for-gravitational-waves), December 3, 2016, TACC press release.

