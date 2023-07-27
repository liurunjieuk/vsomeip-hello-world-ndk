cmake_minimum_required(VERSION 3.4.1)

project(vsomeip-hello-world)

list(APPEND CMAKE_MODULE_PATH ${CMAKE_SOURCE_DIR}/cmake)

add_subdirectory(external/boost-cmake-ndk)
add_subdirectory(external/vsomeip-ndk)
add_subdirectory(external/vsomeip-ndk/examples/hello_world)
add_subdirectory(vsomeip-hello-world/app/src/main/cpp)
