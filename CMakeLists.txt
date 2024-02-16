cmake_minimum_required(VERSION 3.10)  # Minimum version of CMake required

project(SimpleHelloWorld)  # Name of your project

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(SimpleHelloWorld HelloWorldStarter.cpp)  # Create an executable from source file main.cpp


