IfcOpenShell binaries will be required during compilation of IFC Component

Compilation IfcOpenShell from source files:

Prerequisites:
IfcOpenShell requires Open CASCADE Technology and boost installed on your station

To compile IfcOpenShell by CMake GUI you should follow the next steps:

1. Define source code folder (C:/IfcOpenShell/cmake_no_exec)

2. Define build folder (C:/IfcOpenShell/build)
Execute configure

3. Ungrouped Entries - OCC_INCLUDE_DIR Ц define path at include files of Open CASCADE Technology
Execute configure
Ungrouped Entries - OCC_LIBRARY_DIR entity will appear in CMake GUI interface 

4. - define path at libraries of Open CASCADE Technology
Execute configure
Boost entity will appear in CMake GUI interface 

5. Define Boost_INCLUDE-DIR as boost_1_67/include/boost-1_67
    Define Boost_Library_DIR до папки boost_1_67/lib

6. Define CMAKTE- define CMAKE_INSTALL_PREFIX as path to folder where ifc4 will be installed

7. Check that BUILD_SHARED_LIBS и USE_IFC4 are checked
Execute generate

8. Open project IfcOpenShell.sln
Build
Install

9. Copy boost folder with include files from boost_1_67/include/boost-1_67 to installed include folder of IfcOpenShell
