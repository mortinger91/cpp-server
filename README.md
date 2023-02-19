[![cpp-server](https://github.com/mortinger91/cpp-server/actions/workflows/cmake.yml/badge.svg?branch=master)](https://github.com/mortinger91/cpp-server/actions/workflows/cmake.yml)

<h1>cpp-server</h1>
Easy CMake C++ project that uses sockets. Supports Linux and macOS.
<h2>Set up project:</h2>
Execute script:

```./ProjectFolder/scripts/cmake_build.sh```<br>
or execute task "build_cmake" in VSCode.
<h2>Build and Run:</h2>
Execute script:

```./ProjectFolder/scripts/make_debug.sh```<br>
then run:<br>
```./ProjectFolder/build/debug/bin/cpp-server```<br>
or select and run a configuration in VSCode:<br>
- Debug<br>
- Release
<h2>Run tests:</h2>
Execute script:

```./ProjectFolder/scripts/run_tests.sh```<br>
or execute task "run_tests" in VSCode.
<h2>Add a new file:</h2>
- Create the new file in the desired folder.<br>
- Add file.cpp in the CMakeLists.txt file (the one in the same folder as the file).<br>
- If adding a new test file, also add add_test() in the tests/CMakeLists.txt file.
