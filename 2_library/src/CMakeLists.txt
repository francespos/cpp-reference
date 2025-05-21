add_library(lib STATIC hello.cpp)

target_include_directories(lib PUBLIC ../include)

set_property(TARGET lib PROPERTY CXX_STANDARD 14)