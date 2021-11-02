# dh_certificate
This repository contains materials that support the Northeastern University graduate certificate in Digital Humanities. At the moment, this is in its second year and going strong.

## Organization
The directory structure serves a few different pedagogical purposes:
* to provide sufficient depth of directories to support some experimentation with navigation using cd, etc.
* to demonstrate one possible rational way of organizing files (with data organized into incoming, working, and final versions, and with a separate "output" area for exports into other formats)

## Contents
The contents of the repository are currenty designed to support a two-class unit on command-line tools and regular expressions. In the first class session, we explore basic Unix commands: navigating around the directory structure, creating and deleting files and directories, and manipulating files in simple ways using e.g. cat, uniq and sort. In the second class session, we focus on regular expressions, using the test files to practice simple searches and global changes.

Specific materials include:
* in data/incoming/ there are three different lists of names that include first and last names and birth and death dates; names_list3.txt uses different formatting. With these we can practice concatenation, uniquing, sorting, and also (in the regular expressions unit) making global changes to the arrangement of the third file so that it can be integrated with the other two. 
* also in data/incoming there are two files intended for the regex experimentation, which in addition to names and dates include occupations to allow greater scope for experimentation. This file also includes some special characters. 
* in data/working there are some intermediary versions of files, just to demonstrate the function of the directory
* in data/final there are some final versions of files, just to demonstrate the function of the directory
* in output/ there are two samples of possible output formats, including TSV and CSV, just to demonstrate the principle
* in messy_archive/ there are a number of files with deliberately chaotic filenames, to support a short hands-on exercise to practice renaming, moving, copying, and concatenating files as part of data management.
