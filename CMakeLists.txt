project(gamekeeper-files NONE)
cmake_minimum_required(VERSION 2.8)

if(UNIX)
  include(GNUInstallDirs)
endif()

install(DIRECTORY stores DESTINATION ${CMAKE_INSTALL_FULL_DATADIR}/gamekeeper)
