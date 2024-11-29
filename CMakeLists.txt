cmake_minimum_required(VERSION 3.30.5)
project(epoll_chat_server
        VERSION 0.1
        DESCRIPTION "epoll chat server by cpp"
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 26)

include_directories(.)

add_subdirectory(src)