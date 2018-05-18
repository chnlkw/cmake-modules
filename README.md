# cmake-modules
cmake modules like: FindNUMA

# Package includes

- NUMA

# Usage

```sh
    git submodule add https://github.com/chnlkw/cmake_modules.git
```

```cmake
set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} ${CMAKE_CURRENT_SOURCE_DIR}/cmake_modules)

find_package(NUMA)

if (NUMA_FOUND)
    add_definitions(-DNUMA)
endif ()

```