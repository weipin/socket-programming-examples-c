add_executable(simple-client client.cc)
target_include_directories(simple-client PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(simple-server server.cc)
target_include_directories(simple-server PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})
