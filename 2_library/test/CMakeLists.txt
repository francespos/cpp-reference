enable_testing()

add_executable(test test.cpp)

target_link_libraries(test PRIVATE lib)

set_property(TARGET test PROPERTY CXX_STANDARD 14)

add_test(NAME Test COMMAND test)