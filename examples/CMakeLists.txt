# GLFW
add_library(imgui_impl_glfw OBJECT)
target_sources(imgui_impl_glfw
    PUBLIC
        imgui_impl_glfw.h
    PRIVATE
        imgui_impl_glfw.cpp
)
target_include_directories(imgui_impl_glfw
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)
target_link_libraries(imgui_impl_glfw
    PRIVATE
        imgui_core
        glfw
)

# OpenGL3
add_library(imgui_impl_opengl3 OBJECT)
target_sources(imgui_impl_opengl3
    PUBLIC
        imgui_impl_opengl3.h
    PRIVATE
        imgui_impl_opengl3.cpp
)
target_include_directories(imgui_impl_opengl3
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)
target_link_libraries(imgui_impl_opengl3
    PUBLIC
        libglew_static
    PRIVATE
        imgui_core
)