# For more information about build system see
# https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/build-system.html
# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(camera)

# Add the include directory for i2c_master.h
include_directories("C:/Espressif/frameworks/esp-idf-v5.3/components/esp_driver_i2c/include")
