cmake_minimum_required(VERSION 2.6)

Project(Test)

FIND_PACKAGE(VXL REQUIRED)

INCLUDE(${VXL_CMAKE_DIR}/UseVXL.cmake)

ADD_EXECUTABLE(Test Test.cpp)

TARGET_LINK_LIBRARIES(Test vul rrel)
