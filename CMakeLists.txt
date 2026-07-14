cmake_minimum_required(VERSION 3.20)

# aCore - CMSIS 核心头文件库
add_library(aCore INTERFACE)

target_include_directories(aCore
    INTERFACE
        ${CMAKE_CURRENT_SOURCE_DIR}/Core/Include
        ${CMAKE_CURRENT_SOURCE_DIR}/Device/ST/STM32H7xx/Include
)
