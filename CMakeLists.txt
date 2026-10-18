cmake_minimum_required(VERSION 4.3)
project(LegacyOpenGLLoader LANGUAGES C)

set(CMAKE_C_STANDARD 23)

add_library(LegacyOpenGLLoader STATIC src/glad.c)
target_include_directories(LegacyOpenGLLoader PUBLIC include)