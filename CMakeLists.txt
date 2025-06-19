cmake_minimum_required(VERSION 3.15)
project(PersonalFinanceManager VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Inclui diretórios
include_directories(include)

# Adiciona os arquivos fonte
file(GLOB SOURCES "src/*.cpp")

add_executable(finance-manager ${SOURCES})

