cmake_minimum_required (VERSION 2.6) 
include_directories(${CMAKE_CURRENT_SOURCE_DIR})
ADD_LIBRARY(gp STATIC getopt.c getopt1.c getline.cc hash.cc)
