# Build System
Experiment and compare various of build system (mainly for `C/C++`), such as [GNU autotools](https://en.wikipedia.org/wiki/GNU_Autotools), [cmake](https://cmake.org/), [ninja](https://ninja-build.org/), [gn](https://gn.googlesource.com/gn), [bazel](https://bazel.build/), etc.      


## cmake 
See more in [cmake_vs_gnu_autotools (Chinese)](./cmake_vs_gnu_autotools/).    

## GNU autotools
See more in [gnu_autotools_test (Chinese)](./gnu_autotools_test/) and [cmake_vs_gnu_autotools (Chinese)](./cmake_vs_gnu_autotools/).     

## ninja 
Born for [Chromium](https://www.chromium.org/), focus on performance: super fast!     

- https://ninja-build.org/

## gn 
Designed for large projects that generates build files for `ninja`.

- https://gn.googlesource.com/gn
- https://gn.googlesource.com/gn/+/main/docs/quick_start.md
- https://gn.googlesource.com/gn/+/main/docs/reference.md
- https://gn.googlesource.com/gn/+/refs/heads/main/examples/simple_build/

## bazel
TODO:     

## blade     
[chen3feng/blade-build](https://github.com/chen3feng/blade-build) is inspired by Google's public information about their build system [build in cloud: how build system works](http://google-engtools.blogspot.hk/2011/08/build-in-cloud-how-build-system-works.html). It looks very similiar with `gn/bazel` at the moment, and also uses `ninja` as backend in the current version.            

See more in [blade_test/quick-start](blade_test/quick-start).      

## waf
TODO:   

## scons
[scons](https://github.com/SCons/scons).      

TODO:      

## meson     
[meson](https://mesonbuild.com/).      

TODO:    
