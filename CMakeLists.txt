cmake_minimum_required(VERSION 3.22)
project(ray_tracer)

set(CMAKE_CXX_STANDARD 17)

file(GLOB_RECURSE ONE_FILES "day-one/*.cc" "day-one/*.h")
file(GLOB_RECURSE TWO_FILES "day-two/*.cc" "day-two/*.h")
file(GLOB_RECURSE THREE_FILES "day-three/*.cc" "day-three/*.h")

add_executable(one ${ONE_FILES})
add_executable(two ${TWO_FILES})
add_executable(three ${THREE_FILES})

