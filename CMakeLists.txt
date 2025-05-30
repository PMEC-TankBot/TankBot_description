cmake_minimum_required(VERSION 3.5)
project(tankbot_description)

find_package(ament_cmake REQUIRED)

# Instala URDF, meshes, launch, etc.
install(DIRECTORY urdf meshes
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
