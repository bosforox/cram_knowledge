##############################################################################
# CMake
##############################################################################

cmake_minimum_required(VERSION 2.8.3)
project(cram_knowledge)

find_package(catkin REQUIRED COMPONENTS dul)

catkin_package(CATKIN_DEPENDS dul)

##############################################################################
# Catkin
##############################################################################

install(DIRECTORY owl/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/owl)

