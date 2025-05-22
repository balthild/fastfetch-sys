add_subdirectory(vendor)

add_library(fastfetch-vendor)
target_link_libraries(fastfetch-vendor libfastfetch)
