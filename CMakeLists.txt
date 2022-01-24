cmake_minimum_required(VERSION 3.5)
project(dht22-esp-idf)

add_library(dht22-esp-idf SHARED src/DHT.c include/DHT.h)
target_include_directories(dht22-esp-idf PUBLIC include)