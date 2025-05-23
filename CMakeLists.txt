cmake_minimum_required(VERSION 3.15)

idf_component_register(SRCS "Time/Time.cpp"
                      INCLUDE_DIRS "Time"
                      REQUIRES arduino-esp32
                      )