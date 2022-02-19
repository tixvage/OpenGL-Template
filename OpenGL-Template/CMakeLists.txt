add_executable(OpenGL-Template src/main.cpp)

target_link_libraries(
            OpenGL-Template
            
            PRIVATE
            EnTT::EnTT
            imgui
            glm::glm
            glfw
            glad
)
