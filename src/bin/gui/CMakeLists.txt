remake_qt5()
remake_qt5_include()

remake_add_executables(LINK seekthermal ${QT_QTCORE_LIBRARY}
  ${QT_QTGUI_LIBRARY})
