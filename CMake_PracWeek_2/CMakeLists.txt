# CMakeList.txt : CMake project for CMake_PracWeek_2, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (CMake_PracWeek_2 "CMake_PracWeek_2.cpp" "CMake_PracWeek_2.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET CMake_PracWeek_2 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
