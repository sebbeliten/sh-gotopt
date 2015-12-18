#sh-gotopt

##Usage
```
COPY COMPACT alias'D VERSION TO YOUR SCRIPT,  ALSO COPY ARGUMENT handlerS IF YOU WANT OPTARG.
EXAMPLE IN sh-gotopt ILLUSTRATES HOW TO USE IT.
```

##Synopsis
It's like getopt.  Features:
* supports long options
* supports multiple connected short options
* also, with the gotarg argument handler,  an argument may occur directly after a short option,  no space required
* u can write ur own argument handlerS,  one is just an alias later referenced
* tries to be sh compatible
* doesn't use external programS,  just shell

##Compatibility (tested)
* [NO] dash (2 instances of ${OPTOPT:2} and 1 instance of ${OPTOPT:1} causes this incompatibility)
* [OK] bash
* [OK] busybox ash
