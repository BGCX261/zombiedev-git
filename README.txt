Development tools :
    -Cmake

-----------------------------

Project compilation : 

Release mode : 
    cd ./build/release-build/
    cmake -DCMAKE_BUILD_TYPE=Release ./../trunk/
    make

Debug mode : 
    cd ./build/debug-build/
    cmake -DCMAKE_BUILD_TYPE=Debug ./../trunk/
    make

-----------------------------

Launch the application : 
    cd ./build/*-build/core
    ./main

-----------------------------

Clean the build directory before any commit : 
    rm -rf ./build/*-build/*


-----------------------------

QTCREATOR MODE HANDLING

open project : choose zombieDev/trunk/CMakeLists.txt

-Release (open first time): 
    build directory = zombieDev/trunk/build/release-build
    option : -DCMAKE_BUILD_TYPE=Release

-Debug : 
Projects -> Build Settings -> Add -> Build
    build directory = zombieDev/trunk/build/debug-build
    option : -DCMAKE_BUILD_TYPE=Debug

Don't commit CMakeLists.txt.user !!
