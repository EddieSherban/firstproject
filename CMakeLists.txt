cmake_minimum_required(VERSION 3.13)
project(firstproject	VERSION 0.1.0
			DESCRIPTION "starting to blink an LED"
			LANGUAGES C CXX)

add_executable(${firstproject} main.c)

