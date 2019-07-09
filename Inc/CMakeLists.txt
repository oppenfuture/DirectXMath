cmake_minimum_required (VERSION 3.8)
project(DirectXHeader LANGUAGES CXX)

file(GLOB SRC *.h *.inl)

install(FILES ${SRC} DESTINATION /usr/local/include)