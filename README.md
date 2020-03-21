# googletest-x86_x64
Native Visual Studio solution and project files to compile in Windows x86/x64/Release/Debug

# Background #
The standard googletest distribution uses Bazel or CMake. This does
not generate good solution/project files, especially needs to be
configured for x86/x64 separately.

I also standardize the options used to the ones in my other projects,
including OutDir, IntDir, Runtime (DLL) etc.

# Installation #

  * git clone [googletest, tested w/ v1.10.x](https://github.com/google/googletest.git)
  * Create a folder called build in this directory
  * git clone [googletest-x86_x64](https://github.com/sridharb1/googletest-x86_x64.git)
    to another folder
  * Copy the contents of the folder above to the build folder

