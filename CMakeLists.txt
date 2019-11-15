cmake_minimum_required (VERSION 3.0)
project (ar9300_eeprom)

include_directories(include)

file(GLOB ar9300_eeprom_src "*.c")

add_executable(ar9300_eeprom ${ar9300_eeprom_src})
