# evmone: Fast Ethereum Virtual Machine implementation
# Copyright 2018-2019 The evmone Authors.
# SPDX-License-Identifier: Apache-2.0

add_subdirectory(evmone)

SET(CMAKE_BUILD_TYPE "Debug")  
SET(CMAKE_CXX_FLAGS_DEBUG "$ENV{CXXFLAGS} -O0 -Wall -g2 -ggdb")  
SET(CMAKE_CXX_FLAGS_RELEASE "$ENV{CXXFLAGS} -O3 -Wall")  
