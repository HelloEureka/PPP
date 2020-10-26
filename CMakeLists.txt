cmake_minimum_required(VERSION 3.17)
project(PPP)

# 添加math库
LINK_LIBRARIES(m)

#set(CMAKE_CXX_STANDARD 14)
set(CMAKE_C_STANDARD 99)

AUX_SOURCE_DIRECTORY(./src SRC_LIST)

add_executable(PPP ${SRC_LIST})
