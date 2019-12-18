add_executable(client client.cc echo-client.cc)
target_include_directories(client PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})

add_executable(server server.cc echo-server.cc)
target_include_directories(server PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})
