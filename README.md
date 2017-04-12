PyCBC is a software package used to explore astrophysical sources of gravitational waves. It contains algorithms that can detect coalescing compact binaries and measure the astrophysical parameters of detected sources. PyCBC was used in the [first direct detection of gravitational waves by LIGO](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.061102) and is used in the ongoing analysis of LIGO and Virgo data.  PyCBC was featured in [Physics World](http://live.iop-pp01.agh.sleek.net/2017/02/26/why-we-should-give-credit-to-code%E2%80%AFcreators/) as a good example of a large collaboration publishing its research products, including its software.

The easiest way to start using PyCBC is to install one of our [Docker containers.](https://hub.docker.com/u/pycbc/) Install the [Docker Community Edition](https://www.docker.com/community-edition) for your [Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac?tab=description) or [Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows?tab=description) desktop, then type the commands shown below. Docker CE installations for [Linux platforms](https://www.docker.com/community-edition#/download) are also available.

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


## Documentation

See the [latest documentation](pycbc/latest/html/) built from the [source code](https://github.com/ligo-cbc/pycbc) for more instructions on how to get started, including setting up a Docker container that can [display graphics](http://ligo-cbc.github.io/pycbc/latest/html/docker.html) from PyCBC programs.

## Use of PyCBC in Scientific Publications
Please site using the [guidelines here](http://ligo-cbc.github.io/pycbc/latest/html/credit.html) if you use PyCBC in your publications ore reference our work.

[![PyPI version](https://badge.fury.io/py/PyCBC.svg)](https://badge.fury.io/py/PyCBC)
[![Build Status](https://travis-ci.org/ligo-cbc/pycbc.svg?branch=master)](https://travis-ci.org/ligo-cbc/pycbc)
[![Code Health](https://landscape.io/github/ligo-cbc/pycbc/master/landscape.svg?style=flat)](https://landscape.io/github/ligo-cbc/pycbc/master)
[![Research software impact](http://depsy.org/api/package/pypi/PyCBC/badge.svg)](http://depsy.org/package/python/PyCBC)




