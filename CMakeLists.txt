CU_SET_PATH("CMAKE_MOD_CUSTOMLOGIN_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/mod_customlogin.cpp")

AC_ADD_SCRIPT_LOADER("CustomLogin" "${CMAKE_CURRENT_LIST_DIR}/src/loader_customlogin.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/mod_customlogin.conf.dist")
