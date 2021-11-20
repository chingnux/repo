ChinGNUx repository
===========================

This is the package repository of the `ChinGNUx <https://chingnux.org/>`_ project.

The main source repository of this project is at https://notabug.org/chingnux/repo.

The packages in this repository must meet these requirements:

1. Use fixed version packages, do not use VCS (e.g. -git) packages.
2. All the packages must be built offline after all the dependencies are installed
   and the source code is downloaded. Use source code with vendor code bundled when needed.
3. When source code with a reliable signature or hash checksum is available, use it
   instead of the code archived by third party services such as GitHub.
