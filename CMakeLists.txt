project(FCC-config)

include(GNUInstallDirs)

install(DIRECTORY ${CMAKE_CURRENT_LIST_DIR}/FCCee/ DESTINATION ${CMAKE_INSTALL_DATADIR}/${CMAKE_PROJECT_NAME})
