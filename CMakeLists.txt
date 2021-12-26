cmake_minimum_required(VERSION 3.0)

project(UFOS)

add_executable(UFOS ../ufos.c++ ../src/init.c++ ../src/loop.c++ ../src/ufo.c++ ../src/player.c++ ../src/intro.c++)

target_link_libraries(UFOS sfml-system sfml-window sfml-graphics sfml-audio)