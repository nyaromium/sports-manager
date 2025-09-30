
add_executable(gui
    main.cpp
)

target_link_libraries(gui
PUBLIC
    OpenXLSX::OpenXLSX
    wx::core
    wx::base
)