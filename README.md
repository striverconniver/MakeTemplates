# **MakeTemplates**
This repository includes Make templates and include files for building C/C++
projects under Linux and Mac OS X. Libraries, archives, shared libraries
and executables can be **made** with the help of files in this repository.

These template files rely on environment variable CODE_TOP to be defined
and set to the directory which contains the following directory structure:

$(CODE_TOP)
* AlguileBin - this directory holds project scripts and tools
* XPlat - 'XPlat' is an abbreviation for 'cross-platform'; this directory keeps all the cross-platform library source trees that is private to this project
* XPlat-Ext - 'Ext' is an abbreviation for 'external'; this directory keeps all the cross-platform library source trees that are shared with the world at large
* Lib/X64 - this directory keeps all the platform-dependent library source trees; the assumption is that we are only building for 64-bit archtectures
* Apps/X64 - this directory keeps all the application source trees; again, the assumption is that we are only building for 64-bit architectures

The AlguileBin directory is a separate GIT repository and can be obtained
[here](https://github.com/striverconniver/AlguileBin.git).

   

