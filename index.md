---
layout: page
title: "https://raw.githubusercontent.com/gwastro/pycbc-logo/master/pycbc_logo_name.png"
subtitle: Free and open software to study gravitational waves.
use-site-title: true
---

<img src="img/gw170817.png" alt="Drawing" style="width: 100%;"/>

PyCBC is a software package used to explore astrophysical sources of gravitational waves. It contains algorithms that can detect coalescing compact binaries and measure the astrophysical parameters of detected sources. PyCBC was used in the [first direct detection of gravitational waves by LIGO](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.061102) and is used in the ongoing analysis of LIGO and Virgo data.  PyCBC was featured in [Physics World](http://live.iop-pp01.agh.sleek.net/2017/02/26/why-we-should-give-credit-to-code%E2%80%AFcreators/) as a good example of a large collaboration publishing its research products, including its software.

## Use of PyCBC

If you use PyCBC in your scientific publications or projects, we ask that you acknowlege our work by citing the publications that describe  PyCBC and the software's [digital object identifier](https://zenodo.org/badge/latestdoi/31596861), as described in the
 [PyCBC citation guidelines.](http://pycbc.org/pycbc/latest/html/credit.html)

## Getting Started
You can start using the PyCBC library now in an interactive notebook! [See our tutorials](https://github.com/gwastro/PyCBC-Tutorials)


One way to start using PyCBC on your computer is to install one of our [Docker containers.](https://hub.docker.com/u/pycbc/) Install the [Docker Community Edition](https://www.docker.com/community-edition) for your [Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac?tab=description) or [Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows?tab=description) desktop, then type the commands shown below. Docker CE installations for [Linux platforms](https://www.docker.com/community-edition#/download) are also available.

<script src="https://cdn.rawgit.com/mattboldt/typed.js/v1.1.7/js/typed.js" charset="utf-8"></script>
<script type="text/javascript">
	document.addEventListener("DOMContentLoaded", function(){
		Typed.new(".element", {
			strings: ["^500<strong>docker pull pycbc/pycbc-el7:latest</strong><br>$ ^500<strong>docker run -it pycbc/pycbc-el7:latest</strong><br>&#40;pycbc-software&#41;&#91;pycbc@37184573e664 &#126;&#93;$ ^500<strong>python</strong><br>Python 2.7.5 &#40;default, Nov  6 2016, 00:28:07&#41;<br>&#91;GCC 4.8.5 20150623 &#40;Red Hat 4.8.5-11&#41;&#93; on linux2<br>&gt;&gt;&gt; ^500<strong>execfile&#40;&quot;/opt/pycbc/src/pycbc/examples/waveform/match_waveform.py&quot;&#41;</strong><br>^1000The match is: 0.953<br>&gt;&gt;&gt; ^500<strong>from pycbc.waveform import td_approximants</strong><br>&gt;&gt;&gt; ^500<strong>print td_approximants&#40;&#41;&#91;20:24&#93;</strong><br>['SEOBNRv3', 'SEOBNRv2', 'SpinTaylorT1', 'SEOBNRv4']<br>&gt;&gt;&gt; "],
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
[![Build Status](https://travis-ci.org/gwastro/pycbc.svg?branch=master)](https://travis-ci.org/gwastro/pycbc)
[![Code Health](https://landscape.io/github/gwastro/pycbc/master/landscape.svg?style=flat)](https://landscape.io/github/gwastro/pycbc/master)
