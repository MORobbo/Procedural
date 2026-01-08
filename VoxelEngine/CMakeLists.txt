project(my_cpp_app VERSION 1.0)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

file(GLOB SOURCES "src/*.cpp")

add_executable(my_cpp_app ${SOURCES})

enable_testing()

add_subdirectory(tests)