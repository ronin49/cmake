cmake_minimum_required(VERSION 3.23)
include(FetchContent)
FetchContent_Declare(
lol
GIT_REPOSITORY https://github.com/ronin49/test.git
GIT_TAG main
)

FetchContent_MakeAvailable(lol)
