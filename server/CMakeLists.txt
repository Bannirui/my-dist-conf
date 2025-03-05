project(server LANGUAGES C CXX)

# 头文件
include_directories(inc)
# 源文件
file(GLOB_RECURSE srcs "${CMAKE_CURRENT_SOURCE_DIR}/*.cpp")

add_executable(${PROJECT_NAME}
    ${srcs}
)