# clinfo
clinfo with cmake

## Introduction  
This is a code with cmake build from https://github.com/simleb/clinfo  
More easy to compile.  

## Build  
```bash
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

Then you will find clinfo binary, just execute it.  
The lib directory supply windows binary OpenCL.lib.  
For linux or Mac, you can use apt or other libOpenCL packages put in the "lib" dir.  

## Download  
clinfo for windows  
https://github.com/engineer1109/clinfo/releases/tag/v1.0  
