add_library(Logging STATIC log.c)
#target_sources(Logging PUBLIC log.h)
target_include_directories(Logging INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
#target_compile_definitions(Logging PRIVATE LOG_USE_COLOR)