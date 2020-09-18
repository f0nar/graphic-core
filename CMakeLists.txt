# CMakeList.txt: файл проекта CMake верхнего уровня; проведите глобальную конфигурацию
# и включите сюда подпроекты.
#
cmake_minimum_required (VERSION 3.8)

project(gcore)

add_library(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME})