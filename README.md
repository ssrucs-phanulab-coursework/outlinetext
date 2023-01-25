# SSRUCS CS Outlines and Notes - A Living Text

## Overview

This online text is prepared and built based on the Jupyter Book, A Jupyter Projects and GitHub Pages by GitHub kindly hosts the same. The design, format and styling and a portion of the contents were made available from the github repositories of eDesigned by [Melanie Walsh](https://melaniewalsh.org/) and for which we are gratefully acknowledged.

This repository hosts the the program codes mainly in Pyton with an limited small portions of Julias for the online text, *SSRUCS CS Outlines and Notes - A Living Text*, which provides detailed introduction to the all selected topics explicitly described according to the undergraduate program of study in computer science's curriculum, however, only limited courses and subjects taught out by teaching staffs of the PhanuLAB from semester 2 of the academic year 2022 onward. In lieu of that being mentioned, this will be from time to time updated to reflect the contents expanded, revised, or archived not only in response to the changes in contents themselves but also the teaching assignments and scopes, henceforth, the repository name and/or title, the living text. The contents to appear are initially centered around discrete mathematics, algorithms, data science, programming implementations of the preceedings, mainly in python and part of julia programmiong languages and the academic english. Subsequent topics related to computer organization and architecture and optimization are actively planned.

Python and Julia implemention demonstrations are being actively integrated in classroom use so that fufilling students engagements via interactions are sufficiently met supporting both regular inclass activities as well as learning reinforcement activities undertaken outside the classroom.

A recognizabled portion of the text is dedicated to the introductory contents made available on GitHub originally created to support "Introduction to Cultural Analytics: Data, Computation & Culture," an undergraduate course taught at Cornell University and the University of Washington, obtained via cloning are presented in its original forms without any modifications with proper attributions retaining the authors and her affiliations strictly remain intact with once again expressed here our sincere grateful appreciation and acknowledgement of the meaningful efforts.

The book is intended for SSRUCS students so the contents are featured in Thai. However, some will be available in bilingual of Thai and English and at the minimum is solely available in English.

## Jupyter Book Overview and Repository Structure

The Python package [`jupyter-book`](https://jupyterbook.org/intro.html#install-jupyter-book) processes the Jupyter notebook files from this repository and outputs them as the publication-quality HTML files that generate the [corresponding a living csnotes and text website](https://ssrucs-phanulab-coursework.github.io/csoutlines-notes/).

The HTML files are currently hidden in this branch of the GitHub repository, but you can find them in the [gh-pages branch](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/tree/gh-pages).

Below I will briefly explain the structure of this repository and some important Jupyter Book features.

- [`/book`](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/tree/main/book) contains all the materials that generate the Jupyter Book
- [`/binder`](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/tree/master/binder) contains materials that set up the virtual [Binder](https://mybinder.org/) environment for running Jupyter notebooks in the cloud

### Configuration file

The configuration file [`/book/_config.yml`](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/blob/master/book/_config.yml) is where I establish key features of the book, such as the title, logo, and whether users can open the Jupyter notebook files in the cloud.

### Table of Contents file

The table of contents file [`/book/_toc.yml`](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/blob/master/book/_toc.yml) establishes the table of contents structure on the left-hand side of the web page.

### Data

Data can be can be found in [`/book/data`](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/tree/master/book/data)

### Texts

Texts can be can be found in [`/book/texts`](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/tree/master/book/texts)

### Custom CSS

Custom CSS styling can be found in [`/book/_static/custom.css`](https://github.com/ssrucs-phanulab-courseork/csoutlines-notes/blob/master/book/_static/custom.css) (it's a bit messy at the moment, sorry)

## Learn More About Jupyter Book

You can learn more about Jupyter Book by exploring the documentation: <https://jupyterbook.org/intro.html>

## Acknowledgments

This course was inspired by a range of excellent course materials, including those by [Lauren Klein](https://github.com/laurenfklein/emory-qtm340), [David Mimno](https://mimno.infosci.cornell.edu/info3350/), and [Allison Parrish](https://github.com/aparrish/rwet). The section "Working with Languages Beyond English" was co-authored with [Quinn Dombrowski](http://www.quinndombrowski.com/).

## License

This book is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Support This Project

We are pleased and honored to make available this book freely. However, if you find it useful, and if you'd like to support its continued development and maintenance, you can be part of this project by contributing to the new contents, erradata, and others using directly the available GitHub issue requests residing in this repository.
