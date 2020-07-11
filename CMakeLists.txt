# CMake 最低版本号要求

cmake_minimum_required (VERSION 2.8)


# 项目信息

project (mytest)

# 指定生成目标
add_executable(mytest test.cpp)
target_link_libraries(mytest gtest gmock pthread)
