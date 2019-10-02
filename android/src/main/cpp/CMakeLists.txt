cmake_minimum_required(VERSION 3.4.1)

add_library(process-frame SHARED
            process-frame.cpp)

# Include libraries needed for process-frame lib
target_link_libraries(process-frame
                      android
                      log)