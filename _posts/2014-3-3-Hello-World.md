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

Author: Mardochee Reveil <a href="https://pubs.rsc.org/en/content/articlelanding/2018/me/c8me00003d#!divAbstract">(research paper)</a> <br>
SEING is distributed as free and open-source code available on <a href="https://github.com/mreveil/seing">github</a>. 

### Python wrapping
A function wrapper basically provides a different way to use wrapped object. Ex: a simpler interface, or some added functionality.<br>
Since the package was build in C/C++, my main task would involve building a python wrapper for it.<br>
You may ask, **WHY PYTHON** ? Python is highly productive even though it is much slower when being computed. It is easy to code in, hence it's popularity.

There are various methods to build a wrapper like manual, using SWIG, pyrex, pyBind11 etc. (something we will decide very soon).


## Week 2 : Learning new thing!
This internship has given me a platform to learn so many things that are vital for all programmers but I hadn't tried simply because of the lack of an opportunity to use those skills.
### Git and GitHub tutorials
Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. <br>
Here are a few GitHub resources you may checkout if you are starting out as suggested by my mentor: <br>
1.<a href="https://docs.github.com/en/get-started/quickstart/set-up-git"> Setting up</a> <br>
2.<a href="https://github.com/firstcontributions/first-contributions:"> Learn about making contribution</a>
### GitHub pages
GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub. This is what I am using to make this blog. It is wasy to use, and a great way to document your projects!
## Week 3: Back to business!
After what seemed to be a very tedious and cumbersome installation process came the time to actually use the package.<br> 
The research on python wrappers followed that. The top options were: pyBind11 and SWIG.
We finally decided to go for pybind11.<br>  
-It supports classes.<br> 
-It handles polymorphic subclassing.<br> 
-It allows you to add dynamic attributes to objects from Python and many other tools, which would be quite difficult to do from the C-based tools you’ve examined.<br> 



