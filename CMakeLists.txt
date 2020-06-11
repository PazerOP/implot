project(implot)

add_library(implot
	implot.cpp
	implot.h
	implot_demo.cpp
)

target_link_libraries(implot imgui)
target_include_directories(implot PUBLIC .)
