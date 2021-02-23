add_library(pico_graphics types.cpp pico_graphics.cpp)
target_include_directories(pico_graphics INTERFACE ${CMAKE_CURRENT_LIST_DIR})