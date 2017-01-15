

To build this app use the CMake to generate project files for your IDE, then build the project in your IDE.
NOTE: You will need to have OpenCV built with OpenGL support in order to run the demo 

----------------------------------------------------------
How to enable OpenGL Support in OpenCV
----------------------------------------------------------
 * Linux:   Execute "sudo apt-get install libgtkglext1 libgtkglext1-dev" first.
 
----------------------------------------------------------
Building the project using CMake from the command-line:
----------------------------------------------------------
Linux:
    export OpenCV_DIR="~/OpenCV/build"
    mkdir build
    cd build
    cmake -D OpenCV_DIR=$OpenCV_DIR ..
    make 


    
----------------------------------------------------------
Running the project:
----------------------------------------------------------
Just execute "EXAMPLE_MARKERLESS_AR".

