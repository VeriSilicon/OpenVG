option(OPENVG_DBG_INFO "Include debugging information in the binary." OFF)

set(OPENVG_PLATFORM "rt1170" CACHE STRING "Compile OpenVG for this platform.")
set_property(CACHE OPENVG_PLATFORM PROPERTY STRINGS "rt1170")

set(MCU_SDK_VER "2.15.x" CACHE STRING "Compile for this version of MCU-SDK.")
set_property(CACHE MCU_SDK_VER PROPERTY STRINGS "2.15.x;2.16.x")

add_subdirectory(${OPENVG_PLATFORM})
