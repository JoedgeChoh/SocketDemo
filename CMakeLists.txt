cmake_minimum_required(VERSION 2.6)
project(SocketDemo)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

add_executable(server src/server.c)
add_executable(client src/client.c)


