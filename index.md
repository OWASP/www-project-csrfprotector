---
layout: col-sidebar
title: OWASP CSRFProtector Project
tags: php, apache
level: 2
type: library
---
<!-- rebuild -->
[![Todo Status](http://todofy.org/b/mebjas/CSRF-Protector-PHP)](http://todofy.org/r/mebjas/CSRF-Protector-PHP) [![Build Status](https://travis-ci.org/mebjas/CSRF-Protector-PHP.svg?branch=master)](https://travis-ci.org/mebjas/CSRF-Protector-PHP) 

### Introduction
OWASP CSRF Protector Project is an effort by a group of developers in securing web applications against Cross Site Request Forgery, providing php library and an Apache Module (to be used differently) for easy mitigation.

 - GitHub Repo - [PHP Library](https://github.com/mebjas/CSRF-Protector-PHP)
 - GitHub Repo - [Apache Module](https://github.com/mebjas/CSRF-Protector-PHP)
 
### What is CSRF Protector?
CSRF Protector Project has two parts:

 1. Apache 2.x.x Module: An Apache Module which can be easily installed and configured in an Apache Server to protect it from CSRF vulnerabilities.
 2. php library: A standalone php library which can be integrated with any existing web application or used while creating a new php project. All developer need to do is include the library and call the initiating function. [View More](https://github.com/mebjas/CSRF-Protector-PHP/wiki)

Its based on the research paper [A Server and Browser-Transparent CSRF Defense for Web 2.0 Applications - ACSAC 2011](http://www3.cs.stonybrook.edu/~rpelizzi/jcsrf.pdf)

### How to use
 - [How to use on Github Wiki](https://github.com/mebjas/CSRF-Protector-PHP/wiki/How-to-use)
 - [Gihub wiki](https://github.com/mebjas/CSRF-Protector-PHP/wiki/)
 
### Features Offered
CSRF Protection provide protection for:

 - Normal HTML forms (POST/GET)
 - Normal Get requests (Not enabled by default)
 - Ajax Requests (XHR)
 - Dynamically generated forms
 
### Damages Mitigated: Cross Site Request Forgery
CSRF Protector provides mitigation against Cross Site Request Forgery a.k.a CSRF or XSRF.

### Major Contributors
 - [Minhaz](mailto:minhaz@owasp.org)
 - [Kevin W Wall](mailto:kevin.w.wall@owasp.org)
 - [Abbas Naderi](mailto:abiusx@owasp.org)
 - [Jim Manico](mailto:jim.manico@owasp.org)
 - Abhinav Dahiya
