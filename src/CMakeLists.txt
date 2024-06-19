project(src)

add_executable(src main.cpp)

include_directories(../includes)

target_link_libraries(src includes)

