add_executable(gfx_engine main.cpp)

find_package(glfw3 REQUIRED)

target_link_libraries(gfx_engine glfw)

target_sources(gfx_engine PRIVATE
    glad.c
    func.cpp
)