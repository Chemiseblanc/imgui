# # Allegro5
# add_library(impl_allegro5 STATIC)
# target_sources(impl_allegro5
#     PUBLIC
#         imgui_impl_allegro5.h
#     PRIVATE
#         imgui_impl_allegro5.cpp
# )
# target_include_directories(impl_allegro5
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_allegro5
#     PRIVATE
#         imgui
# )

# # DirectX 9
# add_library(impl_dx9 OBJECT)
# target_sources(impl_dx9
#     PUBLIC
#         imgui_impl_dx9.h
#     PRIVATE
#         imgui_impl_dx9.cpp
# )
# target_include_directories(impl_dx9
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_dx9
#     PRIVATE
#         imgui
# )

# # DirectX 10
# add_library(impl_dx10 OBJECT)
# target_sources(impl_dx10
#     PUBLIC
#         imgui_impl_dx10.h
#     PRIVATE
#         imgui_impl_dx10.cpp
# )
# target_include_directories(impl_dx10
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_dx10
#     PRIVATE
#         imgui
# )

# # DirectX 11
# add_library(impl_dx11 OBJECT)
# target_sources(impl_dx11
#     PUBLIC
#         imgui_impl_dx11.h
#     PRIVATE
#         imgui_impl_dx11.cpp
# )
# target_include_directories(impl_dx11
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_dx11
#     PRIVATE
#         imgui
# )

# # DirectX 12
# add_library(impl_dx12 OBJECT)
# target_sources(impl_dx12
#     PUBLIC
#         imgui_impl_dx12.h
#     PRIVATE
#         imgui_impl_dx12.cpp
# )
# target_include_directories(impl_dx12
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_dx12
#     PRIVATE
#         imgui
# )

# GLFW
add_library(impl_glfw OBJECT)
target_sources(impl_glfw
    PUBLIC
        imgui_impl_glfw.h
    PRIVATE
        imgui_impl_glfw.cpp
)
target_include_directories(impl_glfw
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)
target_link_libraries(impl_glfw
    PRIVATE
        imgui
)

# # GLUT
# add_library(impl_glut OBJECT)
# target_sources(impl_glut
#     PUBLIC
#         imgui_impl_glut.h
#     PRIVATE
#         imgui_impl_glut.cpp
# )
# target_include_directories(impl_glut
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_glut
#     PRIVATE
#         imgui
# )

# # Marmalade
# add_library(impl_marmalade OBJECT)
# target_sources(impl_marmalade
#     PUBLIC
#         imgui_impl_marmalade.h
#     PRIVATE
#         imgui_impl_marmalade.cpp
# )
# target_include_directories(impl_marmalade
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_marmalade
#     PRIVATE
#         imgui
# )

# # Metal
# if (APPLE)
# add_library(impl_metal OBJECT)
# target_sources(impl_metal
#     PUBLIC
#         imgui_impl_metal.h
#     PRIVATE
#         imgui_impl_metal.mm
# )
# target_include_directories(impl_metal
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_metal
#     PRIVATE
#         imgui
# )
# endif()

# # OpenGL2
# add_library(impl_opengl2 OBJECT)
# target_sources(impl_opengl2
#     PUBLIC
#         imgui_impl_opengl2.h
#     PRIVATE
#         imgui_impl_opengl2.cpp
# )
# target_include_directories(impl_opengl2
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_opengl2
#     PRIVATE
#         imgui
# )

# OpenGL3
add_library(impl_opengl3 OBJECT)
target_sources(impl_opengl3
    PUBLIC
        imgui_impl_opengl3.h
    PRIVATE
        imgui_impl_opengl3.cpp
)
target_include_directories(impl_opengl3
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)
target_link_libraries(impl_opengl3
    PRIVATE
        imgui
)

# # OSX
# if (APPLE)
# target_sources(impl_osx
#     PUBLIC
#         imgui_impl_osx.h
#     PRIVATE
#         imgui_impl_osx.mm
# )
# target_include_directories(impl_osx
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_osx
#     PRIVATE
#         imgui
# )
# endif()

# # SDL
# target_sources(impl_sdl
#     PUBLIC
#         imgui_impl_sdl.h
#     PRIVATE
#         imgui_impl_sdl.cpp
# )
# target_include_directories(impl_sdl
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_sdl
#     PRIVATE
#         imgui
# )

# # Vulkan
# target_sources(impl_vulkan
#     PUBLIC
#         imgui_impl_vulkan.h
#     PRIVATE
#         imgui_impl_vulkan.cpp
# )
# target_include_directories(impl_vulkan
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_vulkan
#     PRIVATE
#         imgui
# )

# # Win32
# if (WIN32)
# target_sources(impl_win32
#     PUBLIC
#         imgui_impl_win32.h
#     PRIVATE
#         imgui_impl_win32.cpp
# )
# target_include_directories(impl_win32
#     PUBLIC
#         ${CMAKE_CURRENT_SOURCE_DIR}
# )
# target_link_libraries(impl_win32
#     PRIVATE
#         imgui
# )
# endif()