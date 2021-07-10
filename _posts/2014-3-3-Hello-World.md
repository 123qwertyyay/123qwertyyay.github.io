---
layout: post
title: About this blog
published: true
---
I am currently (summers'2021) doing a research internship under <a href="https://clancygroup.wse.jhu.edu/">Prof. Paulette Clancy</a> at Johns Hopkins University, United states. This blog is meant to keep a track of the same. My mentor/ PhD Supervisor for this internship is - Divya Sharma.

## Week 1 : What is molecular finger printing?
Molecular fingerprints are a way of encoding the structure of a molecule. There are many fingerprinting techniques available like gaussian, zernike, bispectrum etc and that gave the motivation to build SEING. 
### SEING
<a href="https://seing.readthedocs.io"> SEING</a> is a C/C++ package for fingerprint calculations suitable for machine learning studies of molecular systems. SEING was developed in <a href="http://clancygroup.cbe.cornell.edu/" >the Clancy Group</a> at Cornell University.

Author: Mardochee Reveil 

<a href="https://pubs.rsc.org/en/content/articlelanding/2018/me/c8me00003d#!divAbstract">The research paper</a> on SEING.<br>
SEING is distributed as free and open-source code available on <a href="https://github.com/mreveil/seing">github</a>. 

### Python wrapping
A function wrapper basically provides a different way to use wrapped object. Ex: a simpler interface, or some added functionality.<br>
Since the package was build in C/C++, my main task would involve building a python wrapper for it. There are various methods to build a wrapper like manual, using SWIG, pyrex pyBind11 etc. (something we will decide very soon).
