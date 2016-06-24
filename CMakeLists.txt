
cmake_minimum_required(VERSION 3.3)

project(SimpleSignals) 

add_executable(stest test.cpp SimpleSignal.h)

target_compile_features(stest PUBLIC cxx_range_for cxx_variadic_templates)


