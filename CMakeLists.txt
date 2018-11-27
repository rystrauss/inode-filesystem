cmake_minimum_required(VERSION 3.12)
project(inode_filesystem C)

set(CMAKE_C_STANDARD 11)

add_executable(inode_filesystem tester.c storage.c files.c bitmap.c)