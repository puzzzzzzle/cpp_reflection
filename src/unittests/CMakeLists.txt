aux_source_directory(. cpps)
include_directories(.)

add_executable(unittests ${cpps})