cmake_minimum_required(VERSION 3.18)

cmake_policy(SET CMP0011 NEW)
cmake_policy(SET CMP0025 NEW)
cmake_policy(SET CMP0048 NEW)
cmake_policy(SET CMP0067 NEW)

project(vkdt VERSION 1.0 LANGUAGES CXX C)

add_executable(vkdt src/cli/main.c)
