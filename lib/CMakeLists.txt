include(${PROJECT_SOURCE_DIR}/deps/asio.cmake)

add_library(cmusclient
    cmus_client.cc
    cmus_client.h
    connection_interface.h
    exceptions.cc
    exceptions.h
    ip_connection_interface.cc
    ip_connection_interface.h
    metadata.cc
    metadata.h
    status.cc
    status.h
    string_buffer.h
    tags.cc
    tags.h
    unix_connection_interface.cc
    unix_connection_interface.h
)
