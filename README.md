# **MakeTemplates**
This repository includes Make templates and include files for building C/C++
projects under Linux and Mac OS X. Libraries, archives, shared libraries
and executables can be **made** with the help of files in this repository.

These template files rely on environment variable CODE_TOP to be defined
and set to the directory which contains the following directory structure:

$(CODE_TOP)
* AlguileBin - this directory holds project scripts and tools
* XPlat - this is an abbreviation for cross-platform; this directory keeps all the cross-platform source trees that is private to this project
* XPlat-Ext - the 'Ext' suffix indicates cross-platform source trees that is shared with the world at large
* Lib/X64
* Apps/X64

The AlguileBin directory is a separate GIT repository and can be obtained
[here](https://github.com/striverconniver/AlguileBin.git).

   

