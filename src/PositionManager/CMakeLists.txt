
qt_add_library(PositionManager STATIC
	PositionManager.cpp
	PositionManager.h
	SimulatedPosition.cc
	SimulatedPosition.h
)

target_link_libraries(PositionManager
	PUBLIC
		qgc
)

target_include_directories(PositionManager
	PUBLIC
		${CMAKE_CURRENT_SOURCE_DIR}
	)

