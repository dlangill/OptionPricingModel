cmake_minimum_required(VERSION 3.13) 
project(OptionPricingModel)             
set(CMAKE_CXX_STANDARD 20)         

# Add main.cpp file of the project root directory as a source file
set(SOURCE_FILES src/main.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(model ${SOURCE_FILES})