cmake_minimum_required(VERSION 2.8)

project(linenoise C)

add_library(linenoise linenoise.c)

source_group("Header Files" FILES linenoise.h)
source_group("Source Files" FILES linenoise.c)
