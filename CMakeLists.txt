cmake_minimum_required(VERSION 3.5)

project(Zork14 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Zork14
    Character.cpp Character.h CMakeLists.txt CMakeLists.txt.user Command.cpp Command.h CommandWords.cpp CommandWords.h item.cpp item.h  Parser.cpp Parser.h Room.cpp Room.h ZorkUL.cpp ZorkUL.h
    Character.cpp Character.h CMakeLists.txt CMakeLists.txt.user Command.cpp Command.h CommandWords.cpp CommandWords.h item.cpp item.h  Parser.cpp Parser.h Room.cpp Room.h ZorkUL.cpp ZorkUL.h
    Character.cpp Character.h CMakeLists.txt.user Command.cpp Command.h CommandWords.cpp CommandWords.h item.cpp item.h Parser.cpp Parser.h Room.cpp Room.h ZorkUL.cpp ZorkUL.h
    class2.h class2.cpp
    arrowpad.h arrowpad.cpp)

include(GNUInstallDirs)
install(TARGETS Zork14
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
