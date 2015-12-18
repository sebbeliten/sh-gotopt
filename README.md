#sh-gotopt - command line option and argument parser

##Usage
COPY COMPACT alias'D VERSION TO YOUR SCRIPT,  ALSO COPY ARGUMENT handlerS IF YOU WANT OPTARG.
EXAMPLE IN sh-gotopt ILLUSTRATES HOW TO USE IT.

##Synopsis
* long option support: --option
* short option support: -o
* concatenated short option support: -oO
* short option with concatenated argument support: -oARGUMENT
* concatenated short option with concatenated argument support: -oOARGUMENT
* POSIX compatible
* entirely written in sh

##Compatibility (tested)
* [OK] dash
* [NO] bash `#only works when,  shopt -s expand_aliases
* [OK] busybox ash
