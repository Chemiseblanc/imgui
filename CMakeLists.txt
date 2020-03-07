cmake_minimum_required(VERSION 3.15)

project(imgui
    LANGUAGE CXX
)

add_library(imgui STATIC)
target_sources(imgui
    PUBLIC
        imgui.h
        imgui.cpp
    PRIVATE
        imgui_draw.cpp
        imgui_widgets.cpp
        imgui_internal.h
        imstb_rectpack.h
        imstb_textedit.h
        imstb_truetype.h
)
target_include_directories(imgui
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)

add_subdirectory(examples)

export(TARGETS imgui impl_opengl3 impl_glfw NAMESPACE imgui)