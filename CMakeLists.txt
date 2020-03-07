cmake_minimum_required(VERSION 3.15)

project(imgui
    LANGUAGES CXX
)

add_library(imgui STATIC)
target_sources(imgui_core
    PUBLIC
        imgui.h
        imgui.cpp
        imconfig.h
    PRIVATE
        imgui_draw.cpp
        imgui_widgets.cpp
        imgui_internal.h
        imstb_rectpack.h
        imstb_textedit.h
        imstb_truetype.h
)
target_include_directories(imgui_core
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)

add_subdirectory(examples)

export(TARGETS imgui_core imgui_impl_opengl3 imgui_impl_glfw NAMESPACE imgui:: FILE DearImgui.cmake)