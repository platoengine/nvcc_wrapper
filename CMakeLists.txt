############ Project setup ##################################################
CMAKE_MINIMUM_REQUIRED(VERSION 3.0.0)
#############################################################################

project(NvccWrapper)

configure_file(nvcc_wrapper ${CMAKE_INSTALL_PREFIX}/etc/nvcc_wrapper @ONLY)
