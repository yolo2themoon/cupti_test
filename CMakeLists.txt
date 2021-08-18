cmake_minimum_required(VERSION 2.8)
project(cupti_test)
find_package(CUDA REQUIRED)

include_directories("/usr/local/cuda/include")
link_directories("/usr/local/cuda/lib64")

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")

# Pass options to NVCC
list(APPEND CUDA_NVCC_FLAGS "-std=c++17")
list(APPEND CUDA_NVCC_FLAGS "-v")


cuda_add_executable(callback
    extensions.cpp
    callback.cpp
    kernel.cu
)
target_link_libraries(callback cudart)
target_link_libraries(callback cuda)
target_link_libraries(callback nvperf_host)
target_link_libraries(callback cupti)

cuda_add_executable(autorange
    extensions.cpp
    autorange.cpp
    kernel.cu
)
target_link_libraries(autorange cudart)
target_link_libraries(autorange cuda)
target_link_libraries(autorange nvperf_host)
target_link_libraries(autorange cupti)
