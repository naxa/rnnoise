
set(INCLUDE_DIR
    ${PROJECT_SOURCE_DIR}/include
)
include_directories(${INCLUDE_DIR})

file(GLOB RN_SRC
  *.c
)

add_library(rnnoise STATIC ${RN_SRC})
