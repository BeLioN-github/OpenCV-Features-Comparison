file(GLOB AGAST_SOURCE_FILES "${CMAKE_CURRENT_SOURCE_DIR}/*.cc")
file(GLOB AGAST_HEADER_FILES "${CMAKE_CURRENT_SOURCE_DIR}/*.h")

add_library(agast ${AGAST_SOURCE_FILES} ${AGAST_HEADER_FILES})

