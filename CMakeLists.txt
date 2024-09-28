cmake_minimum_required(VERSION 3.25)
project(cpp_starter LANGUAGES CXX)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake")

include(MyProjectOptions)

include(StructureOnly)
structure_only(
  DIRECTORIES
  src
  test
)