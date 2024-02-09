add_library(cryptoppwin SHARED IMPORTED GLOBAL)
set_target_properties(cryptoppwin PROPERTIES IMPORTED_IMPLIB "${CMAKE_CURRENT_SOURCE_DIR}/lib/cryptlib.lib")