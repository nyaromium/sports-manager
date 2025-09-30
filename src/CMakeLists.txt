
add_executable(gui
    main.cpp
)

if(WIN32)
    set_target_properties(gui PROPERTIES WIN32_EXECUTABLE ON)
endif()


target_link_libraries(gui
PUBLIC
    OpenXLSX::OpenXLSX
    wx::core
    wx::base
)