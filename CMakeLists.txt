cmake_minimum_required(VERSION 3.16)
project(Udeabook LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(include)

add_executable(Udeabook
    src/main.cpp
    src/Foto.cpp
    src/Medidor.cpp
    include/Foto.h
    include/Medidor.h
    include/Lista.h
    include/Album.h
)