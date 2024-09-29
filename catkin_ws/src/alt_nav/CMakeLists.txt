cmake_minimum_required(VERSION 3.0.2)
project(alt_nav)

## Find catkin macros and libraries
find_package(catkin REQUIRED COMPONENTS
  move_base
)

###################################
## catkin specific configuration ##
###################################
## Declare catkin package
catkin_package(
  CATKIN_DEPENDS move_base
)

###########
## Build ##
###########

## Specify additional locations of header files
include_directories(
  ${catkin_INCLUDE_DIRS}
)

#############
## Install ##
#############

# Uncomment this block only if you're defining and installing executables
# Mark executables for installation
# install(TARGETS ${PROJECT_NAME}_node
#   RUNTIME DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
# )

#############
## Testing ##
#############

# Uncomment this block if you're adding unit tests
# Add gtest based cpp test target and link libraries
# catkin_add_gtest(${PROJECT_NAME}-test test/test_alt_nav.cpp)
# if(TARGET ${PROJECT_NAME}-test)
#   target_link_libraries(${PROJECT_NAME}-test ${PROJECT_NAME})
# endif()
