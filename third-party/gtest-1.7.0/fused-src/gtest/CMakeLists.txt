add_library(gtest gtest-all.cc)
target_compile_definitions(gtest PUBLIC -DGTEST_HAS_TR1_TUPLE=0 -DGTEST_HAS_STD_TUPLE=1)
target_include_directories(gtest PUBLIC )
