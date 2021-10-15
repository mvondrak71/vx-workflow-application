# Copyright (c) 2020 Wind River Systems, Inc. All Rights Reserved.
#
cmake_minimum_required(VERSION 3.10.2)
project(philosophersRTP)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -static")
set(CMAKE_EXECUTABLE_SUFFIX ".vxe")
aux_source_directory("src" DIR_SRCS)
add_executable (philosophersRTP ${DIR_SRCS} )
