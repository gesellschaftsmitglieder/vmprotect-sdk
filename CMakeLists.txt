cmake_minimum_required(VERSION 3.21)

project(vmprotect-sdk)

add_library(vmprotect-sdk INTERFACE)

target_include_directories(vmprotect-sdk INTERFACE .)
target_link_libraries(vmprotect-sdk INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/VMProtectSDK32.lib)
