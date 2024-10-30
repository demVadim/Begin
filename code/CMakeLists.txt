# general info
add_executable(${PROJECT_NAME})

# sources
target_compile_features(${PROJECT_NAME} PRIVATE cxx_std_20)
target_sources(${PROJECT_NAME}          PRIVATE main.cpp)



