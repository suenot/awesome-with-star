# Information comes from [onqtam/awesome-cmake](https://github.com/onqtam/awesome-cmake)
# Awesome CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/onqtam/awesome-cmake/master/cmake-logo.svg" align="right" width="100">](https://cmake.org/)

> A curated list of awesome [CMake](https://cmake.org/) scripts, modules, examples and others

Your contributions are highly welcome (first see [CONTRIBUTING.md](CONTRIBUTING.md)).

## Contents

- [Community](#community)
- [Resources](#resources)
- [Package Management / Build Systems](#package-management--build-systems)
- [Modules](#modules)
- [Utility Scripts](#utility-scripts)
- [Toolchains](#toolchains)
- [Examples / Templates](#examples--templates)
- [Other](#other)

## Community

* [```#cmake``` on Freenode](http://webchat.freenode.net/?channels=cmake)
* [```/r/cmake``` on Reddit](https://www.reddit.com/r/cmake/)
* [```/r/cpp``` on Reddit](https://www.reddit.com/r/cpp/)
* [Mailing Lists](https://cmake.org/mailing-lists/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/cmake)

## Resources

* [Latest Documentation](https://cmake.org/cmake/help/latest/)
* [FAQ](https://cmake.org/Wiki/CMake_FAQ)
* [Wiki](https://cmake.org/Wiki/CMake)
* [Webinars](https://cmake.org/webinars/)
* [Web Book](https://github.com/ruslo/CGold) - CGold: The Hitchhiker’s [Guide](https://cgold.readthedocs.io) to the CMake. [```[BSD2]```][BSD-2-Clause] :star:176
* [Modern CMake](https://github.com/toeb/moderncmake) - Modern CMake **PDF** and samples by the creator of [cmakepp](https://github.com/toeb/cmakepp). [```[MIT]```][MIT] :star:118
* [Article](http://foonathan.net/blog/2016/03/03/cmake-install.html) - Easily supporting CMake install and find_package().
* [Article](http://foonathan.net/blog/2016/07/07/cmake-dependency-handling.html) - Easy dependency management for C++ with CMake and Git.
* [Article](https://steveire.wordpress.com/2016/08/09/opt-in-header-only-libraries-with-cmake/) - Opt-in header-only libraries with CMake.
* [Article](https://rix0r.nl/blog/2015/08/13/cmake-guide/) - Ultimate Guide to Modern CMake.
* [Article](http://voices.canonical.com/jussi.pakkanen/2013/03/26/a-list-of-common-cmake-antipatterns/) - A list of common CMake antipatterns (from 2013 but still relevant).
* [Article](http://preshing.com/20170511/how-to-build-a-cmake-based-project/) - How to Build a CMake-Based Project.
* [Article](http://preshing.com/20170522/learn-cmakes-scripting-language-in-15-minutes/) - Learn CMake's Scripting Language in 15 Minutes.
* [Article](http://aosabook.org/en/cmake.html) - The architecture of CMake.
* [Lecture](https://www.youtube.com/watch?v=bsXLMQ6WgIk) - Effective CMake - by Daniel Pfeifer, C++Now 2017.
* [Article](https://devblogs.nvidia.com/parallelforall/building-cuda-applications-cmake/) - Building Cross-Platform CUDA Applications with CMake.
* [Tutorial](https://github.com/Wigner-GPU-Lab/Teaching/tree/master/CMake) - A step-by-step guide for understanding CMake. :star:22
* [Article + Lecture](https://steveire.wordpress.com/2017/11/05/embracing-modern-cmake/) - Embracing Modern CMake - by Stephen Kelly.
* [Lecture](https://www.youtube.com/watch?v=eC9-iRN2b04) - Modern CMake for Modular Design - by Mathieu Ropert, CppCon 2017.
* [Article](https://juan-medina.com/2017/07/01/moderncppci/) - Modern C++ CI (although it uses non-modern CMake like ```include_directories()```).
* [Article](https://pabloariasal.github.io/2018/02/19/its-time-to-do-cmake-right/) - It's Time To Do CMake Right (one of the best articles about CMake).
* Articles - A series on CMake - by Martin Hořeňovský
    * [Basic CMake usage](https://codingnest.com/basic-cmake/).
    * [Basic CMake, part 2: libraries](https://codingnest.com/basic-cmake-part-2/).
* [Lecture](https://www.youtube.com/watch?v=jt3meXdP-QI) - Introduction to CMake - by Florent Castelli, C++ Sweden 2018.
* [Article](http://bastian.rieck.me/blog/posts/2018/cmake_tips/) - Some nice and accurate CMake tips.
* [Article](http://unclejimbo.github.io/2018/06/08/Modern-CMake-for-Library-Developers/) - Modern CMake for Library Developers.
* [Article](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1) - Effective Modern CMake: a great summary of most good practices - by Manuel Binna.
* [Book](https://crascit.com/professional-cmake/) - Professional CMake: A Practical Guide (paid).
* [Book](https://leanpub.com/effective-cmake) - Effective CMake: Practical Advice to Write Better CMake (not fully written yet).
* [Web Book](https://cliutils.gitlab.io/modern-cmake/) - An Introduction to Modern CMake.
* [YouTube Series](https://vector-of-bool.github.io/2018/08/12/cmake-good.html) - How to CMake Good. [```[CC0-1.0]```][CC0-1.0]

## Package Management / Build Systems

* [hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++ (based on CMake ExternalProject). [```[BSD2]```][BSD-2-Clause] :star:1431
* [cget](https://github.com/pfultz2/cget) - CMake package retrieval. This can be used to download and install CMake packages. [```[BOOST]```][BOOST] :star:258
* [cppan](https://cppan.org/) - C++ Archive Network - C++ Package Manager based on CMake, implemented in C++14. [```[APACHE2]```][APACHE2]
* [cpm](https://github.com/iauns/cpm) - C++ Package Manager based on CMake and Git. [```[MIT]```][MIT] :star:640
* [conan](https://github.com/conan-io/conan) - Conan C++ Package Manager, implemented in Python and has a CMake integration backend. [```[MIT]```][MIT] :star:2249
* [fips](https://github.com/floooh/fips) - High-level build system/dependency management for distributed, multi-platform C/C++ projects. [```[MIT]```][MIT] :star:221
* [Ninja](https://github.com/ninja-build/ninja) - Build system that differs from others in two major respects: it is designed to have its input files generated by a higher-level build system (like CMake), and it is designed to run builds as fast as possible. [```[APACHE2]```][APACHE2] :star:3760
* [vcpkg](https://github.com/Microsoft/vcpkg) - A tool to acquire and build C++ open source libraries. Uses CMake internally as a build script language. [```[MIT]```][MIT] :star:4077
* [pmm](https://github.com/vector-of-bool/pmm) - PMM is a module for CMake that manages... package managers. [```[MIT]```][MIT] :star:31

## Modules

* [cmake-modules](https://github.com/rpavlik/cmake-modules) - [Ryan Pavlik](https://github.com/rpavlik)'s collection of CMake modules. There are a number of find modules, especially for virtual reality and physical simulation, some utility modules, and some patches or workarounds for CMake itself. [```[BOOST]```][BOOST] :star:507
* [cmake-modules](https://github.com/bilke/cmake-modules) - This is a collection of additional CMake modules. Most of them are from Ryan Pavlik. [```[BOOST]```][BOOST] :star:177
* [CMake](https://github.com/Eyescale/CMake) - [Eyescale](https://github.com/Eyescale)'s common CMake modules. [```[BSD3]```][BSD-3-Clause] :star:95
* [sdl2-cmake-scripts](https://github.com/tcbrindle/sdl2-cmake-scripts) - CMake scripts for finding the SDL2, SDL2_image and SDL2_ttf libraries and headers. [```[BSD2]```][BSD-2-Clause] :star:155
* [vfxcmake](https://github.com/nerdvegas/vfxcmake) - CMake Find modules for common vfx software, and general CMake utility code. [```[LGPL]```][LGPL] :star:80
* [cmake-modules](https://github.com/jedbrown/cmake-modules) - CMake modules for some scientific libraries. [```[BSD2]```][BSD-2-Clause] :star:59
* [cgcmake](https://github.com/chadmv/cgcmake) - CMake modules for common applications related to computer graphics. [```[MIT]```][MIT] :star:58
* [FindMathematica](https://github.com/sakra/FindMathematica) - CMake module for Mathematica. [```[MIT]```][MIT] :star:27
* [extra-cmake-modules](https://github.com/KDE/extra-cmake-modules) - [KDE](https://github.com/KDE)'s extra modules and scripts for CMake. [```[BSD3]```][BSD-3-Clause] :star:31
* [FindICU.cmake](https://github.com/julp/FindICU.cmake) - CMake module to find International Components for Unicode (ICU) Library. [```[BSD2]```][BSD-2-Clause] :star:24
* [FindTBB](https://github.com/justusc/FindTBB) - CMake find module for Intel Threading Building Blocks. [```[MIT]```][MIT] :star:59
* [FindWiX](https://github.com/apriorit/FindWiX) - CMake module for building [Windows Installer](https://en.wikipedia.org/wiki/Windows_Installer) packages with [WiX toolset](http://wixtoolset.org). [```[BSD3]```][BSD-3-Clause] :star:4
* [cmake-modules](https://github.com/hanjianwei/cmake-modules) - [hanjianwei](https://github.com/hanjianwei)'s CMake module collection. [```[MIT]```][MIT] :star:24
* [YCM](https://github.com/robotology/ycm) - Extra CMake Modules for [Yet Another Robot Platform](https://github.com/robotology/yarp) and friends. [```[BSD3]```][BSD-3-Clause] :star:19

## Utility Scripts

These provide a wide range of functionality - from dealing with compiler flags to using tools. Some also contain modules.

* [cotire](https://github.com/sakra/cotire) - Cotire (compile time reducer) is a CMake module that speeds up the build process of CMake based build systems by fully automating techniques as precompiled headers and unity builds for C and C++. [```[MIT]```][MIT] :star:861
* [ucm](https://github.com/onqtam/ucm) - For managing compiler/linker flags, collecting sources, precompiled headers, unity builds and others. [```[MIT]```][MIT] :star:124
* [cmakepp](https://github.com/toeb/cmakepp) - Enhancement Suite for the CMake Build System. [```[MIT]```][MIT] :star:297
* [sugar](https://github.com/ruslo/sugar) - CMake tools and examples: collecting source files, warnings suppression, etc. [```[BSD2]```][BSD-2-Clause] :star:81
* [DownloadProject](https://github.com/Crascit/DownloadProject) - CMake module for downloading an external project's source at configure time. [```[MIT]```][MIT] :star:231
* [buildem](https://github.com/janelia-flyem/buildem) - Modular CMake-based system that leverages ExternalProject to simplify builds. [```[LICENSE]```](https://github.com/janelia-flyem/buildem/blob/master/LICENSE.txt) :star:25
* [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake) - Coveralls JSON coverage generator and uploader for CMake. [```[MIT]```][MIT] :star:69
* [compatibility](https://github.com/foonathan/compatibility) - Improved version of cmake-compile-features. [```[LICENSE]```](https://github.com/foonathan/compatibility/blob/master/LICENSE) :star:66
* [cmake-modules](https://github.com/Tronic/cmake-modules) - LibFindMacros development repository and other cool CMake stuff. [```[LICENSE]```](https://github.com/Tronic/cmake-modules/blob/master/LibFindMacros.cmake#L2) :star:27
* [GreatCMakeCookOff](https://github.com/UCL/GreatCMakeCookOff) - This is a repository of useful and less than useful CMake recipes. [```[MIT]```][MIT] :star:24
* [cppcheck-target-cmake](https://github.com/polysquare/cppcheck-target-cmake) - Per-target CPPCheck for CMake. [```[MIT]```][MIT] :star:14
* [clang-tidy-target-cmake](https://github.com/polysquare/clang-tidy-target-cmake) - Add clang-tidy checks to a target using CMake. [```[MIT]```][MIT] :star:10
* [cmake-unit](https://github.com/polysquare/cmake-unit) - Unit testing framework for CMake. [```[MIT]```][MIT] :star:28
* [cmake-header-language](https://github.com/polysquare/cmake-header-language) - CMake macro to determine the language of a header file. [```[MIT]```][MIT] :star:2
* [tooling-cmake-util](https://github.com/polysquare/tooling-cmake-util) - Utility and common library for all polysquare CMake tools. [```[MIT]```][MIT] :star:2
* [iwyu-target-cmake](https://github.com/polysquare/iwyu-target-cmake) - CMake integration for include-what-you-use. [```[MIT]```][MIT] :star:3
* [sanitizers-cmake](https://github.com/arsenm/sanitizers-cmake) - CMake module to enable sanitizers for binary targets. [```[MIT]```][MIT] :star:114
* [cmake-precompiled-header](https://github.com/larsch/cmake-precompiled-header) - Visual Studio and GCC precompiled header macro. [```[LICENSE]```](https://github.com/larsch/cmake-precompiled-header/blob/master/PrecompiledHeader.cmake#L31) :star:92
* [CMakePCHCompiler](https://github.com/nanoant/CMakePCHCompiler) - CMake precompiled headers via custom compiler extension - with reuse support! [```[MIT]```][MIT] :star:51
* [CMake-codecov](https://github.com/RWTH-ELP/CMake-codecov) - Enables code coverage and generates coverage reports with CMake targets. [```[GPL]```][GPL] :star:26
* [leatherman](https://github.com/puppetlabs/leatherman) - Collection of C++ and CMake utility libraries. [```[APACHE2]```][APACHE2] :star:32
* [cmake-get](https://github.com/pfultz2/cmake-get) - Get dependencies in config or script mode. ```[NO LICENSE]``` :star:47

## Toolchains

* [dockcross](https://github.com/dockcross/dockcross) - Cross compiling toolchains in Docker images. [```[MIT]```][MIT] :star:792
* [android-cmake](https://github.com/taka-no-me/android-cmake) - CMake toolchain file and other scripts for the Android NDK. [```[BSD3]```][BSD-3-Clause] :star:918
* [ios-cmake](https://github.com/cristeab/ios-cmake) - Toolchain file and examples using CMake for iOS development. [```[BSD3]```][BSD-3-Clause] :star:214
* [qt-android-cmake](https://github.com/LaurentGomila/qt-android-cmake) - For building and deploying Qt based apps on Android without QtCreator. [```[LICENSE]```](https://github.com/LaurentGomila/qt-android-cmake/blob/master/license.txt) :star:101
* [mingw-w64-cmake](https://github.com/lachs0r/mingw-w64-cmake) - CMake-based MinGW-w64 Cross Toolchain - to build Windows binaries of mpv. [```[ISC]```][ISC] :star:77
* [cmake-avr](https://github.com/mkleemann/cmake-avr) - CMake toolchain for AVR. [```[LICENSE]```](https://github.com/mkleemann/cmake-avr/blob/master/LICENSE) :star:91
* [arduino-cmake](https://github.com/francoiscampbell/arduino-cmake) - This is the CMake project settings for the Arduino platform. [```[MPL]```][MPL] :star:33
* [polly](https://github.com/ruslo/polly) - Collection of CMake toolchain files and scripts for cross-platform build and CI testing. [```[BSD2]```][BSD-2-Clause] :star:480
* [toolchains](https://github.com/mosra/toolchains) - For crosscompiling with CMake. They are meant to be mainly used on ArchLinux. ```[NO LICENSE]``` :star:21
* [cmake](https://github.com/staticlibs/cmake/tree/master/toolchains) - Collection of CMake toolchain files, mostly for static linking. [```[APACHE2]```][APACHE2] :star:6

## Examples / Templates

* [cmake-init](https://github.com/cginternals/cmake-init) - Template for reliable, cross-platform C++ project setup using CMake. [```[LICENSE]```](https://github.com/cginternals/cmake-init/blob/master/LICENSE) :star:318
* [learning-cmake](https://github.com/Akagi201/learning-cmake) - This is a simple CMake practice project which contains some different scenarios. [```[GPL2]```][GPL2] :star:847
* [cmake_test](https://github.com/skebanga/cmake_test) - Small example project using CMake. ```[NO LICENSE]``` :star:14
* [android-cmake](https://github.com/forexample/android-cmake) - Examples of using [ruslo/hunter](https://github.com/ruslo/hunter) package manager for an Android application. [```[BSD2]```][BSD-2-Clause] :star:22
* [hunter-simple](https://github.com/forexample/hunter-simple) - Example of downloading/installing dependencies using [ruslo/hunter](https://github.com/ruslo/hunter) package manager. [```[BSD2]```][BSD-2-Clause] :star:29
* [weather](https://github.com/ruslo/weather) - Example of using [Hunter](http://github.com/ruslo/hunter) cross-platform package manager for CMake to build application which use Boost, CppNetlib.URI, GTest, JSON Spirit. Platforms: Windows (Visual Studio), Linux, Mac OS X + iOS. [```[BSD2]```][BSD-2-Clause] :star:21
* [package-example](https://github.com/forexample/package-example) - Config mode of find_package (examples for [this](http://stackoverflow.com/questions/20746936/cmake-of-what-use-is-find-package-if-you-need-to-specify-cmake-module-path-an) Stack Overflow question). ```[NO LICENSE]``` :star:181
* [CMakeTemplates](https://github.com/OutOfOrder/CMakeTemplates) - Set of initial CMake templates that I use for every game port I work on. ```[NO LICENSE]``` :star:42
* [minimal_cmake_example](https://github.com/krux02/minimal_cmake_example) - Minimal CMake example, that covers dependencies and packaging. [```[CC0-1.0]```][CC0-1.0] :star:102
* [cmake-example](https://github.com/bast/cmake-example) - Example project which demonstrates various CMake features. [```[BSD3]```][BSD-3-Clause] :star:85
* [cmake-examples](https://github.com/ttroy50/cmake-examples) - Useful CMake examples in a tutorial format. [```[MIT]```][MIT] :star:618
* [cmake-templates](https://github.com/district10/cmake-templates) - Some CMake Templates. Qt, Boost, OpenCV, C++11, etc. [```[MIT]```][MIT] :star:208
* [CppProjectTemplate](https://github.com/Barthelemy/CppProjectTemplate) - Basic, but working, C++ project using CMake, boost and Doxygen. [```[MIT]```][MIT] :star:174
* [mini-cmake-qt](https://github.com/euler0/mini-cmake-qt) - Minimal CMake template for Qt 5 projects. [```[LICENSE]```](https://github.com/euler0/mini-cmake-qt/blob/master/LICENSE) :star:106
* [CMake-VisualStudio-Example](https://github.com/cognitivewaves/CMake-VisualStudio-Example) - CMake example for Visual Studio developers - [blog post](http://cognitivewaves.wordpress.com/cmake-and-visual-studio/). ```[NO LICENSE]``` :star:61
* [Cpp-Project-Template](https://github.com/NewProggie/Cpp-Project-Template) - C++ bootstrap project template including CMake build system. [```[MIT]```][MIT] :star:51
* [BASIS](https://github.com/cmake-basis/BASIS) - CMake [BASIS](https://cmake-basis.github.io) makes it easy to create sharable software and libraries that work together. [```[BSD2]```][BSD-2-Clause] :star:17
* [OpenGL_CMake_Skeleton](https://github.com/ArthurSonzogni/OpenGL_CMake_Skeleton) -  A ready to use CMake skeleton using GLFW, Glew and glm. [```[MIT]```][MIT] :star:36
* [coveralls-cmake-example](https://github.com/JoakimSoderberg/coveralls-cmake-example) - Example project for [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake). ```[NO LICENSE]``` :star:17
* [cppbase](https://github.com/kartikkumar/cppbase) - Template for a simple CMake-based C++ project. [```[MIT]```][MIT] :star:97
* [Arduino-CMake-Template](https://github.com/maxbader/Arduino-CMake-Template) - Starting point for Arduino development using CMake. ```[NO LICENSE]``` :star:3
* [c-template](https://github.com/fletcher/c-template) - Boilerplate to set up a c project, include CuTest, CMake build setup. [```[MIT]```][MIT] :star:38
* [cpp_project_template](https://github.com/duckie/cpp_project_template) - Simple template to start quickly a C++ project managed by CMake. [```[MIT]```][MIT] :star:31
* [cpp-boilerplate](https://github.com/Lectem/cpp-boilerplate) - Template that aims to be a reference for modern CMake and CI. [```[MIT]```][MIT] :star:71
* [ci_helloworld](https://github.com/ainfosec/ci_helloworld) - A simple example of how to setup a complete CI environment for C and C++. [```[MIT]```][MIT] :star:169
* [how-to-export-cpp-library](https://github.com/robotology/how-to-export-cpp-library) - An OS-agnostic C++ library template sporting ctest and CI support, written in plain CMake with line-by-line guiding comments. [```[MIT]```][MIT] :star:24
* [ModernCppCI](https://github.com/LearningByExample/ModernCppCI) - An example of doing a Modern C++ project with CI (although it uses non-modern CMake like ```include_directories()```). [```[MIT]```][MIT] :star:65
* [modern-cmake-sample](https://github.com/pabloariasal/modern-cmake-sample) - Best practices and proper usage of CMake by using targets. ```[NO LICENSE]``` :star:149
* [CMakeInstallExample](https://github.com/DeveloperPaul123/CMakeInstallExample) - Installation example for a C++ project (Windows) with Cmake. ```[NO LICENSE]``` :star:10
* [cpp14-project-template](https://github.com/arnavb/cpp14-project-template) - A C++14 template with CI, tests, code coverage, docs and static analysis integration. [```[CC0-1.0]```][CC0-1.0] :star:17
* [cmake_templates](https://github.com/acdemiralp/cmake_templates) - Templates for creating C++ libraries and executables (including conan). ```[NO LICENSE]``` :star:40
* [cmake_snippets](https://github.com/adishavit/cmake_snippets) - Short copy-pasteable CMake snippets. [```[BSD3]```][BSD-3-Clause] :star:24
* [cmake-cookbook](https://github.com/dev-cafe/cmake-cookbook) - A huge CMake cookbook full of recipes. [```[MIT]```][MIT] :star:117
* [cpp-template](https://github.com/joshpeterson/cpp-template) - A template C++ repository, using CMake and Catch. ```[NO LICENSE]``` :star:10

## Other

* [autocmake](https://github.com/coderefinery/autocmake) - Using a autocmake.yml file [Autocmake](http://autocmake.readthedocs.io/en/latest/) composes CMake building blocks into a CMake project and generates CMakeLists.txt as well as a setup script, which serves as a front-end to CMakeLists.txt. [```[BSD3]```][BSD-3-Clause] :star:24
* [UseLATEX](https://github.com/kmorel/UseLATEX) - Collection of CMake macros to simplify building LaTeX files. [```[BSD3]```][BSD-3-Clause] :star:122
* [python-cmake-buildsystem](https://github.com/python-cmake-buildsystem/python-cmake-buildsystem) - Replacement buildsystem for CPython. [```[APACHE2]```][APACHE2] :star:198
* [scikit-build](https://github.com/scikit-build/scikit-build) - Improved build system generator for CPython C extensions. [```[MIT]```][MIT] :star:81
* [protobuf-cmake](https://github.com/jesperes/protobuf-cmake) - CMake build support for Google Protobufs. [```[BSD3]```][BSD-3-Clause] :star:27
* [node-cmake](https://github.com/cjntaylor/node-cmake) - CMake-based build system for node.js native modules. [```[ISC]```][ISC] :star:49
* [cmake-font-lock](https://github.com/Lindydancer/cmake-font-lock) - Advanced syntax coloring support for CMake scripts inside Emacs. [```[GPL]```][GPL] :star:24
* [stm32-cmake](https://github.com/ObKo/stm32-cmake) - Used to develop applications for the STM32 - ST's ARM Cortex-M0(3,4,7) MCUs. [```[MIT]```][MIT] :star:306
* [autovala](https://github.com/rastersoft/autovala) - Program that automatically generates CMake configuration files for your Vala project. [```[GPL]```][GPL] :star:111
* [catkin](https://github.com/ros/catkin) - CMake-based build system that is used to build all packages in Robot Operating System (ROS). [```[BSD3]```][BSD-3-Clause] :star:152
* [suitesparse-metis-for-windows](https://github.com/jlblancoc/suitesparse-metis-for-windows) - CMake scripts for painless usage of SuiteSparse+METIS. [```[BSD3]```][BSD-3-Clause] :star:189
* [cython-cmake-example](https://github.com/thewtex/cython-cmake-example) - Utilities and example for using CMake to build Cython modules. [```[LICENSE]```](https://github.com/thewtex/cython-cmake-example/blob/master/LICENSE) :star:116
* [osg-3rdparty-cmake](https://github.com/bjornblissing/osg-3rdparty-cmake) - CMake scripts for building OpenSceneGraph third party libraries. ```[MIXED LICENSE]``` :star:93
* [cmake-d](https://github.com/dcarp/cmake-d) - CMake for D2. [```[MIT]```][MIT] :star:35
* [cmakeprojectmanager2](https://github.com/h4tr3d/cmakeprojectmanager2) - Enhanced CMake Project Manager plugin for Qt Creator. ```[NO LICENSE]``` :star:46
* [cmake-lint](https://github.com/richq/cmake-lint) - Check for coding style issues in CMake files. cmakelint requires Python. [```[APACHE2]```][APACHE2] :star:68
* [git-cmake-format](https://github.com/kbenzie/git-cmake-format) - Integrate clang-format into your CMake project hosted in a git repository. [```[LICENSE]```](https://github.com/kbenzie/git-cmake-format/blob/master/license.txt) :star:32
* [configure-cmake](https://github.com/nemequ/configure-cmake) - configure-cmake is an autotools-style configure script for CMake-based projects. [```[CC0-1.0]```][CC0-1.0] :star:57
* [tbb](https://github.com/wjakob/tbb) - Threading Building Blocks with CMake build. [```[APACHE2]```][APACHE2] :star:80
* [sqlite.cmake.build](https://github.com/snikulov/sqlite.cmake.build) - CMake script for sqlite amalgamation. ```[NO LICENSE]``` :star:13
* [cmake-ast](https://github.com/polysquare/cmake-ast) - Python module to reduce a CMake file to an AST. [```[MIT]```][MIT] :star:15
* [cmake_format](https://github.com/cheshirekow/cmake_format) - Source code formatter for CMakeLists.txt files. [```[GPL]```][GPL] :star:155
* [cmake-checks-cache](https://github.com/cristianadam/cmake-checks-cache) - CMake checks cache helper modules. [```[MIT]```][MIT] :star:16
* [cmrc](https://github.com/vector-of-bool/cmrc) - A Resource Compiler in a Single CMake Script (compile arbitrary data into a program). [```[MIT]```][MIT] :star:72
* [cmake_check](https://github.com/DaelDe/cmake_check) - Static analysis (linter) for the CMake language (e.g. to enforce modern CMake rules). [```[MIT]```][MIT] :star:8

## License

This is released under the [**```Creative Commons Attribution 4.0 International```**](http://creativecommons.org/licenses/by/4.0/) License ```(CC BY 4.0)```.

[ISC]: https://opensource.org/licenses/ISC
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html
[GPL2]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[MIT]: https://opensource.org/licenses/MIT
[BOOST]: http://www.boost.org/LICENSE_1_0.txt
[BSD-2-Clause]: https://opensource.org/licenses/BSD-2-Clause
[BSD-3-Clause]: https://opensource.org/licenses/BSD-3-Clause
[APACHE2]: http://www.apache.org/licenses/LICENSE-2.0
[CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/
[MPL]: https://www.mozilla.org/en-US/MPL/2.0/

