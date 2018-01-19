cmake_minimum_required(VERSION 2.8)
project(app_project)
#add_executable(myapp *.cpp)
#install(TARGETS myapp DESTINATION bin)

file( GLOB SRCS *.cpp *.h )
add_executable( myapp ${SRCS}) 