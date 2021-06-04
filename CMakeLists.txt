
add_library (student STATIC student.cpp)
add_executable (demo demo.cpp)
target_link_libraries(demo student)
