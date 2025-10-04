cmake_minimum_required(VERSION 3.27)
project(Starter CXX)


build_application(
    SOURCES
    application.cpp

    PACKAGES
    Jolt

    LINK_PACKAGES
    Jolt::Jolt
)

generate_compile_commands()