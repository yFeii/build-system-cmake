
include_directories(build-system-lib/include)
add_definitions(-D TESTMETHOD)

add_library(MathLib build-system-lib/mathLib.c build-system-lib/add/add.c build-system-lib/sub/sub.c)