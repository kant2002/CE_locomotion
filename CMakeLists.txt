cmake_minimum_required(VERSION 3.0) # setting this is required
project(CE_Locomotion)            # this sets the project name

file(GLOB sources      *.cpp *.h)

add_executable(locomotion ${sources})

target_compile_options(locomotion PUBLIC -O3 -flto)

