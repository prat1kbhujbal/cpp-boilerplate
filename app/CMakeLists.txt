add_executable(shell-app main.cpp controller.cpp forward_kinematics.cpp inverse_kinematics.cpp pid.cpp robot.cpp sensor.cpp)

include_directories(
    ${CMAKE_SOURCE_DIR}/include
)
