# The name of our project is "LIBDEMO". CMakeLists files in this
# project can refer to the root source directory of the project as
# ${LIBDEMO_SOURCE_DIR} and to the root binary directory of the
# project as ${LIBDEMO_BINARY_DIR}.
cmake_minimum_required (VERSION 3.2.1)
project (LIBDEMO)

# Recurse into the "src" and "app" subdirectories. This does not actually
# cause another cmake executable to run. The same process will walk through
# the project's entire directory structure.
add_subdirectory (src)
add_subdirectory (app) 
