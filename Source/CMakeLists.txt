
# Debug message
MESSAGE(STATUS "Add subdirectory [${CMAKE_CURRENT_SOURCE_DIR}]")

# Set this directory as ECHO_GAME_ROOT_PATH
SET(ECHO_GAME_ROOT_PATH ${CMAKE_CURRENT_SOURCE_DIR})

# Add game library
ADD_SUBDIRECTORY("${ECHO_GAME_NAME}")

# Add thirdparty libraries


# Add custom editor


