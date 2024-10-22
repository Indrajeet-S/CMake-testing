cmake_minimum_required(VERSION 3.10)

project(my_project VERSION 1.0)

# C standard
set(CMAKE_C_STANDARD 11)

# Include header files
include_directories(include)

# Add the executable
add_executable(my_project src/main.c src/Addbook.c src/Deletebook.c src/issuebook.c src/Searchbook.c src/viewbooks.c)
