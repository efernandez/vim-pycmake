vim-pycmake
===========

Small vim plugin to help working in CMake C/C++ projects

After loading this plugin, vim will scan for a CMake project for any C/C++ source or header file opened. If such a project is found, the include paths generated by CMake will be added to the vim path, and to syntastic include path as well. This enables the use of go-to-file over `#include`s and filename completion, among other nice things.

More features to come.