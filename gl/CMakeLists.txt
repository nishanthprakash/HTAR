
Project(sample)
INCLUDE_DIRECTORIES(/usr/include /usr/include/GL)

ADD_EXECUTABLE(sample HTAR.cpp)
link_directories(/usr/lib)

TARGET_LINK_LIBRARIES(sample GL GLU glut)
