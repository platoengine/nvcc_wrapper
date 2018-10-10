############ Project setup ##################################################
CMAKE_MINIMUM_REQUIRED(VERSION 3.0.0)
#############################################################################

project(NvccWrapper)

configure_file(nvcc_wrapper ${CMAKE_BINARY_DIR}/nvcc_wrapper @ONLY)

install( PROGRAMS ${CMAKE_BINARY_DIR}/nvcc_wrapper DESTINATION ${CMAKE_INSTALL_PREFIX}/etc )
