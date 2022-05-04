add_library (CatCutifier "CatCutifier.cpp" "CatCutifier.h")
add_library (Pear "pear.cpp" "pear.h")
target_include_directories(CatCutifier PUBLIC .)
target_include_directories(Pear PUBLIC .)

# Should install library properly here, but I'm focusing on just the docs