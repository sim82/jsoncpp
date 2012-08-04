set(CMAKE_INCLUDE_CURRENT_DIR ON)
add_subdirectory(json)

SET( JSONCPP_INCLUDE ${CMAKE_CURRENT_SOURCE_DIR} CACHE STRING "jsoncpp include dir" FORCE)
add_library(jsoncpp STATIC jsoncpp.cpp)
