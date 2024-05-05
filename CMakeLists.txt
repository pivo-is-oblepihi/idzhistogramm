cmake_minimum_required(VERSION 3.5)

project(idz LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(QtSWidgets REQUIRED)
add_executable(idz idz.cpp)
target_link_libraries(${PROJECT_NAME} QtS::Widgets)
add_executable(idz main.cpp)
