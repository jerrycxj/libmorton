target_sources(libmorton
  INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/morton_common.h
    ${CMAKE_CURRENT_SOURCE_DIR}/morton_AVX512BITALG.h
    ${CMAKE_CURRENT_SOURCE_DIR}/morton_BMI.h
    ${CMAKE_CURRENT_SOURCE_DIR}/morton2D_LUTs.h
    ${CMAKE_CURRENT_SOURCE_DIR}/morton2D.h
    ${CMAKE_CURRENT_SOURCE_DIR}/morton3D_LUTs.h
    ${CMAKE_CURRENT_SOURCE_DIR}/morton3D.h
    ${CMAKE_CURRENT_SOURCE_DIR}/morton.h
  )