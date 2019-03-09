CMake example project for packaging with Qt5
============================================

 * MacOSX [![Build Status](https://dev.azure.com/miurahr/github/_apis/build/status/miurahr.cmake-qt-packaging-example?branchName=master&jobName=macOS)](https://dev.azure.com/miurahr/github/_build/latest?definitionId=5&branchName=master) 
 * Windows [![Build Status](https://dev.azure.com/miurahr/github/_apis/build/status/miurahr.cmake-qt-packaging-example?branchName=master&jobName=Windows64)](https://dev.azure.com/miurahr/github/_build/latest?definitionId=5&branchName=master)   
 * Ubuntu [![Build Status](https://dev.azure.com/miurahr/github/_apis/build/status/miurahr.cmake-qt-packaging-example?branchName=master&jobName=Ubuntu_1604)](https://dev.azure.com/miurahr/github/_build/latest?definitionId=5&branchName=master) 

This is an example project how to build Qt5 application packages in cross-platform.

The script generate following packages for Qt5 example application.

* Source package
* DMG and tar.bz2 package for OSX
* Null Soft Script Installer (NSIS) installer package for Windows
* NuGet package for windows
* AppImage package for linux
* DEB, RPM and Tar.gz, .bz2 .xz packages for linux

Qt5 example application has bundled Qt5 libraries in packages.


License
-------

MIT license

Copyright (c) 2019 Hiroshi Miura
