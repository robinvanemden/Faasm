add_executable(mem_experiment mem_experiment.cpp)

add_executable(max_mem_experiment max_mem_experiment.cpp)

add_executable(max_thread_experiment max_thread_experiment.cpp)
target_link_libraries(max_thread_experiment pthread)

add_executable(cow_experiment cow_experiment.cpp)

add_executable(rlimit_experiment rlimit_experiment.cpp)

