add_executable(learn-opengl
        main.cpp
)

target_link_libraries(learn-opengl PRIVATE
        glad_gl_core33
        glfw
)