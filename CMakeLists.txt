# Boiler plate setup stuff
cmake_minimum_required(VERSION 3.18)
set(CMAKE_CXX_STANDARD 17)

# Declare the root project
project(lexifier)

# Set source file(s) for our executable
set(SOURCE_FILES main.cpp)

# Declare executable
add_executable(lexify ${SOURCE_FILES})

# Recurse into dependencies
# add_subdirectory( )

# Link dependencies
#target_link_libraries(lexify /*LIB*/)
